# Global Infrastructure

## Regions
- a geographic location where resources can be deployed
- each region is designed to be isolated from other regions

## Selecting a Region
- not all services are availbale in all regions
- make sure to select a region that abides to the same compliance and regualation
- defferent pricing structures
- sometimes laws make you pick a certion region, like the government requireing data to be stored in the country

## Availability Zones (AZ)
- Backups in each region

## Global Content Delivery & Edge Locations
- smaller centers to be closer to customer location
- usually working as CDN's (content delivery solutions)
- much lower latency

## Local Zones
- extensions of AWS Regions
- allows you to use select AWS services, like compute, and storage closer to end-users
- provide high-bandwidth, secure connection to parent AWS region
- great for low latency applications like real-time gaming, live steraming, and virtula workstations for the local city

## Edge loactions vs Local Zones
- Locals are extensions of parent region in major cities
- Own infrastructure
- Edge locations are not tied to parent region. Very small not full sized datacenters
- Use a few specific services usually for content delivery