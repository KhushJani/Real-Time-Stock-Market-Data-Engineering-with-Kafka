# Real-Time-Stock-Market-Data-Engineering-with-Kafka


## Architecture 
![Architecture](https://github.com/KhushJani/Real-Time-Stock-Market-Data-Engineering-with-Kafka/assets/88198216/46a712c8-0580-48e5-88a0-1dce4fbad89c)


## Technology Used
- Programming Language - Python
- Amazon Web Service (AWS)
1. S3 (Simple Storage Service)
2. Athena
3. Glue Crawler
4. Glue Catalog
5. EC2
- Apache Kafka

## Workflow:

* Producer: A Python-based stock market app simulation uses Boto3 to send data to Kafka running on an EC2 instance.
*  Consumer: Kafka consumers process the data, storing it in Amazon S3.
* Data Cataloging: AWS Glue Crawler organizes the data, and Glue Catalog facilitates querying with AWS Athena.

## Steps to Run:

1. Set up the Kafka broker on an EC2 instance.
2. Run the producer script to simulate stock market data and send it to Kafka.
3. Deploy the consumer script to process and store data in S3.
4. Configure AWS Glue Crawler to catalog the data.
5. Use AWS Athena to query the processed data.


# Impact:
Real-time data processing is essential in the financial industry to ensure accurate, timely decision-making and to optimize investment strategies, ultimately leading to improved financial performance and market insights.
