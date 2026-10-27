# Types of Storage
- block storage
- file storage
- object storage

## Block storage
- elastic block storage
- breaks data into blocks and stores those blocks as seperate pieces, each with a unique identifier
- a collection of blocks can be presented to the OS as a volume
- can be presented as a hard drive
- bootable, can install an operating system

## EBS Volumes
- has to be in the same availability zone as the services its connected to

## File storage
- EFS (elastic file storage)
- stores data in a hierarchical structure of files and folders
- can be accessed remotely
- can be mounted but not bootable
- multiple users can connect to same file storage

## Object storage
- objects are just files
- blob storage
- no folder structure
- great for storing logs and media files

## Storage Classes
- s3 standard: most expensive, can handle two simultaneous AZ failures
- s3 standard-IA: has a retrieval fee
- s3 one zone-IA: designed for infreqently accessed data
- s3 Glacier-Instant: used for archiving
- s3 Glacier-Flexible: same but you have to wait to retrieve
- s3 Glacier Deep Archive: used for data that is almost never needed
