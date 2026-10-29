# Application Integration

## Managing Flow
- app to app
- managing flow, quality, buffering, speed between two applications
- manipulating the flow of traffic

## Amazon Simple Notification Service
- used in between two applications when you want to send messages to customers via text, email, or mobile push
- or when you want to copy a single message to multiple applications

## Amazon Simple Queue Service
- when you want to seand a message to another application, but there is a chance that a sudden increase in traffic could generate a large amount of message
- the orders will just queue until your backend can process
- controls flow

## Amazon Elastic Load Balancing
- used to direct traffic to backend servers
- distributes workloads across servers
- traffic distributer

## Amazon Autoscaling
- tracks the number if requests coming in and if it crosses a certain threshold, it increases server count
- can set a minimum and maximum servers