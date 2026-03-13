SkillSphere Cloud Strategy

Background of Enterprise
SkillSphere is an online learning platform where instructors can upload courses and students can access educational content from anywhere. The platform requires reliable hosting, storage for course materials, and a database for managing users and course data.

Current IT Setup
Traditionally, small businesses might host their applications on on-premise servers. This setup requires physical hardware, manual maintenance, and has limited scalability.

Non-Cloud Solution
A non-cloud solution would involve hosting the application on local servers inside the organisation. This requires hardware investment, IT staff for maintenance, and limited ability to scale during high demand.

Cloud Solution Recommendation
Using cloud infrastructure allows the platform to scale automatically as user demand increases. Cloud services also provide better reliability, security and lower infrastructure management.

Architecture
Amazon EC2 (Elastic Compute Cloud) hosts the application server.
Docker is used to run the Nginx web server container.
Amazon RDS (Relational Database Service) stores user and course data.
Amazon S3 (Simple Storage Service) stores course files and static assets.

Justification
Cloud infrastructure provides scalability, high availability and reduced infrastructure management. Using EC2 allows flexible compute resources, RDS simplifies database management, and S3 provides reliable storage for large course files.
