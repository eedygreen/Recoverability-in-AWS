
# Recoverability-In-AWS

### Content

## [Data Durability and Recovery](https://github.com/eedygreen/Recoverability-In-AWS/tree/master/Data%20Durability%20and%20Recovery)

## [Failover and Recovery](https://github.com/eedygreen/Recoverability-In-AWS/tree/master/Failover%20and%20Recovery)

## [Web Resiliency](https://github.com/eedygreen/Recoverability-In-AWS/tree/master/Web%20Resiliency)

**Data Durability and Recovery**
There are two zones used to achieve this project. The Database in the primary zone served as the master and the other in the secondary zone served as the slave.
The Slave gets promoted to Master when there is an outage.

click [here](https://github.com/eedygreen/Recoverability-In-AWS/tree/master/Data%20Durability%20and%20Recovery) to view full details

Availability Estimate
The achievable Recovery Time Objective (RTO) and Recovery Point Objective (RPO) for this Multi-AZ, multi-region database in terms of:

00 - 05: RTO for a single AZ outage = 5 mins (if the fault was detected 5mins after)
05 - 06: Time to restore = 6 mins (one or two mins to restore from last backup)
06 - 36: The minimum RPO for a single AZ is 30 minutes (backup latest restore time)
36 - 37: RPO for a Single region is one minute (1 min) for a month and none within a month.
For a Single AZ, 36-37 mins.

00 - 05: RTO for a Multi AZs outage
05 - 06: Time to restore (one min to restore to latest backup )
06 - 06: RPO for a single failure is None
Multi-AZs has avaliability equivalent to 99.5%-99.9%


**Failover and Recovery**

Clik [here](https://github.com/eedygreen/Recoverability-In-AWS/tree/master/Failover%20and%20Recovery) to view the details.



**Web Resilency**
AWS S3 Versioning was used for reverting Web Application to any point in time when deletion of the Web pages occured

click [here](https://github.com/eedygreen/Recoverability-In-AWS/tree/master/Web%20Resiliency) for details.


[Recoverability in AWS](https://github.com/eedygreen/Recoverability-In-AWS)
