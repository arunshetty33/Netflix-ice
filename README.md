# Netflix ICE

Ice provides a birds-eye view of our large and complex cloud landscape from a usage and cost perspective. Cloud resources are dynamically provisioned by dozens of service teams within the organization and any static snapshot of resource allocation has limited value. The ability to trend usage patterns on a global scale, yet decompose them down to a region, availability zone, or service team provides incredible flexibility. Ice allows us to quantify our AWS footprint and to make educated decisions regarding reservation purchases and reallocation of resources.

# What it does

Ice communicates with AWS Programmatic Billing Access and maintains knowledge of the following key AWS entity categories:

Accounts
Regions
Services (e.g. EC2, S3, EBS)
Usage types (e.g. EC2 - m1.xlarge)
Cost and Usage Categories (On-Demand, Reserved, etc.) The UI allows you to filter directly on the above categories to custom tailor your view.
In addition, Ice supports the definition of Application Groups. These groups are explicitly defined collections of resources in your organization. Such groups allow usage and cost information to be aggregated by individual service teams within your organization, each consisting of multiple services and resources. Ice also provides the ability to email weekly cost reports for each Application Group showing current usage and past trends.

When representing the cost profile for individual resources, Ice will factor the depreciation schedule into your cost contour, if so desired. The ability to amortize one-time purchases, such as reservations, over time allows teams to better evaluate their month-to-month cost footprint.



