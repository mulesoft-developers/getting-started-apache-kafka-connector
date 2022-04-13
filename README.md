<h1 align="center">
	<img
	width="150"
	src="/images/max-terminal.gif"></br>
	Getting Started with the Apache Kafka Connector<br>     
</h1>

<h4 align="center">
	<a href="#overview">Overview</a> |
	<a href="#installation-instructions">Install Me</a> |
	<a href="#faqs">FAQs</a> |
	<a href="#contributing">Contribute</a>
</h4>
	
<h3 align="center">
	Learn how to produce and consume events from an Apache Kafka cluster.<br><br>
</h3>

## Tutorial and Video

For a step by step tutorial navigate to the MuleSoft developer website [here](https://developer.mulesoft.com/tutorials-and-howtos/apache-kafka-connector/getting-started-apache-kafka/)

For a video of the tutorial go [here](https://www.youtube.com/watch?v=5Xd5B_twt9w).

## Overview

In this tutorial, we’ll walk you through how to publish and subscribe to streams of event data moving through an Apache Kafka cluster. You’ll learn how to:
- Setup a managed Apache Kafka cluster on Heroku
- Setup the Apache Kafka Connector configuration
- Subscribe to events on a Kafka topics using the `Message Listener` operation
- Use the `Publish` operation to send messages to Kafka topics

Use the **Apache Kafka Connector** to participate in event driven architectures. De-couple your applications by publishing and subscribing to streams of data moving through distributed event stores like Apache Kafka.

> This sample application is designed to run on MuleSoft's Anypoint Platform.

## Installation Instructions

Install instructions

1. Set up your environment.

<a href="https://anypoint.mulesoft.com/login/signup" ><img width="250" src="/images/start-platform.png"><a>
	
<a href="https://www.mulesoft.com/lp/dl/studio" ><img width="250" src="/images/download-studio.png"><a>

2. Clone this repository.

3. In Anypoint Studio, select `File` > `Import` > `Anypoint Studio` > `Anypoint Studio project from File System` and click Next.

4. Select the cloned repository in the Project Root and make sure to **uncheck** the `Copy project into workspace` option.

5. Click on Finish.
	
6. Create your keystore and truststore files and copy into `src/main/resources`
	
7. Update your Apache Kafka credentials in the local.secure.yaml file. In Anypoint Studio's package explorer open src/main/resources open local.secure.yaml and update the keystore and truststore passwords. Note that password and token should be encrypted (see video and tutorial above for details).

8. Add Runtime Configurations for env and secret.key variables. Set env to local and set encryption.key to be the value used to encrypt your secure property parameters.

## Contributing

Contributions are what make the MuleSoft community such an amazing place. Any contributions you make are **greatly appreciated**.
	
See [contributing.md](/contributing.md) for the MuleSoft Developer principles.
