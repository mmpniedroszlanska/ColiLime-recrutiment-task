#The Importance of Automated Testing in the Firewall Upgrade Process

High digitalization of today’s business and dynamically changing network environments require strong focus on cybersecurity. With continuously evolving network threats, companies need to keep their firewall solutions updated with new features and enhancements which respond to changing security challenges. However, the upgrade process must take into consideration numerous customer-specific elements, which might affect the upgrade efficiency and effectiveness. CodiLime has a solution for this challenge: a customized upgrade process and testing automation.

Adjusting the solution to a specific customer is crucial, as shown with the example presented by Adrian Celebański and Adam Baumeister in their conference talk entitled [“Delivering large-scale operations with Ansible”] (https://www.youtube.com/watch?v=nR4Mljl-cJI&ab_channel=NetworkAutomationForum). Preparing a plan for a healthcare company with 700+ care sites and 140+ hospitals, operating 24h a day, using a variety of platforms and numerous firewalls of different types, versions, and branches, resulting in more than 500 notes, CodiLime faced the following challenges:
-	A large volume of time-consuming upgrade through all sites, platforms, firewall types and versions
-	The complexity of software and hardware to be upgraded
-	Industry specific operation of 24h a day with little time for downtime and low failure tolerance
-	Big failure risks in case of human error in manual upgrade operations

CodiLime approached these challenges with a tailored and automated solution, opting for maximum code and solution reuse, ensuring time efficiency and workload limitation. With its modular structure, the solution can be reused every time an upgrade is needed.
The upgrade process solution presented by Celebański and Baumeister in their conference talk includes the following steps after the user starts an automated upgrade in Ansible:

1.	Readiness checks
2.	Pre-upgrade snapshots and backup
3.	Upgrade
4.	Post-upgrade snapshots
5.	Readiness and comparison tests
6.	Pass or fail decision
7.	Upgrade report generation

The key elements of the process that ensure its reliability and efficiency are checks, snapshots, and tests. Performing checks, you make sure your environment is ready for an upgrade, has proper license, platform connectivity, available disk space, etc. Snapshots taken before and after upgrade allow for post-upgrade comparison tests. Based on tailored comparison tests, the customer can use a safety mechanism of a rollback to the previous version or make sure the upgrade was successful.

The solution created by CodiLime engineers can be adjusted to other customers, as it is based on Ansible playbooks tailored to the customer by:
-	putting modular components together,
-	using open-source modules,
-	creating customer-specific modules based on Ansible playbooks,
-	building testing components from scratch, using their own methodologies for upgrading customer firewalls.

Such a customized and automated solution significantly shortened usually time-consuming upgrade operations and reduced human-error factor typical for manual upgrade. CodiLime solution also offers efficient automated testing, which usually takes the most time and effort of human resources in the case of manual testing. It is a real example of a highly-customizable solution which ensures resource- and time-efficient upgrade across many sites of a complex and extensive company, allowing for its continuous operation.
