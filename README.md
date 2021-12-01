# AWS Compute Decision Tree

With over 170 services to chose from, finding the right AWS compute service can be a challenge. This decision tree will help you find the right AWS compute service for your workload.

Either refer to the flowchart or the storyboard to find the right AWS compute service to suite your needs.

## Storyboard

I found [Storyboard by Viget](https://storyboard.viget.com/) to be a great tool to textualise the decision tree and create a choose your own adventure version of the tree.

[You can access the live version of the storyboard here](https://storyboard.viget.com/aws-compute-decision-tree-2).

Feel free to create your own using the `storyboard.json` file. Simply copy the JSON and click the `Paste` button within the Storyboard.

## Flowchart

The flowcharts are created using the VS Code extension [Draw.io Integration](https://marketplace.visualstudio.com/items?itemName=hediet.vscode-drawio-insiders-build). This extension enables you to create draw.io diagrams from the VS Code editor and have them automatically be saved as Scalable Vector Graphics (SVG).

## Changelog

- 2.1.0:

  - Split flowchart into individual flowcharts based on application (e.g. analytical, application, machine learning).

- 2.0.0:

  - Added support for batch-oriented workloads that require inter-task orchestration serviced by [Amazon Managed Workflows for Apache Airflow](https://aws.amazon.com/managed-workflows-for-apache-airflow/).
  - Added support for edge computing machine learning workloads serviced by [AWS Panorama](https://aws.amazon.com/panorama/) for computer vision and [AWS IoT Greengrass](https://aws.amazon.com/greengrass/) for all other machine learning workloads.
  - Added support for highly concurrent or long-running application workloads serviced by [AWS App Runner](https://aws.amazon.com/apprunner/).
  - Added support for streaming analytical workloads serviced by [Amazon Kinesis Data Analytics](https://aws.amazon.com/kinesis/data-analytics/), [AWS Glue](https://aws.amazon.com/glue/?whats-new-cards.sort-by=item.additionalFields.postDateTime&whats-new-cards.sort-order=desc), [Amazon EMR](https://aws.amazon.com/emr/), and [Amazon EMR Serverless](https://aws.amazon.com/emr/serverless/).
  - Added support for variable and sporadic data warehousing workloads serviced by [Amazon Redshift Serverless](https://aws.amazon.com/redshift/redshift-serverless/).

## Contributing

Think I've made a mistake or have a suggestion? Please let me know by raising an issue.
