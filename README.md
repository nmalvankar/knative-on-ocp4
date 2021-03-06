#  Knative Serving, Eventing and OpenShift Pipelines Tutorial

## Table of Contents

### Installing Knative Components on OCP4
* [Installing Knative Serving, Knative Eventing, OpenShift Pipeline and Client tools](./1.InstallKnativeAndTekton.md)

### OpenShift Pipelines
* [Build an application using OpenShift Pipelines](./2.BuildUsingOpenShiftPipelines.md)

### Knative Serving
* [Deploy Serverless Application](./3.DeployServerlessApp.md)
* [Autoscaling](./4.Autoscaling.md)
* [Blue Green Deployments](./5.BlueGreen.md)
* [Traffic Splitting](./6.TrafficSplitting.md)

### Knative Eventing
* [Add an Event Source for Direct Delivery](./7.AddingDirectEventSource.md)
* [Eventing with Channels and Subscriptions](./8.AddingChannelsAndSubscriptions.md)
* [Eventing with Brokers and Trigger based Subscriptions](./9.UsingBrokersAndTriggers.md)
  
  <a name="kafka"></a>
  #### Using Kafka with Knative Eventing
  * [Configure Kafka Source to receive events from a Kafka Topic](10.KafkaSource.md)
  * [Eventing with Kafka Channel and Subscription](12.KafkaChannelSubscription.md)
  * [Using API Event Source with KafkaChannel Broker and Trigger](11.BrokerTriggerWithKafka.md)

  <a name="awssqs"></a>
    #### Using AWS SQS as Event Source

  * [Configure AWS SQS Source as Direct Source for Knative Service ](13.SQSDirectSource.md)
  *  [Using AWS SQS Source with Broker and Trigger](14.SQSBrokerTrigger.md)