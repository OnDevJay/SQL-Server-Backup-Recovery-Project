# SQL Server Backup Recovery Project
Project demonstrating automated backup and recovery procedures for SQL Server databases

## Aim
The aim of this project is to design and implement an automated backup and recovery system for SQL Server databases, ensuring data integrity, availability, and minimal downtime. By establishing robust backup procedures, the project seeks to provide a reliable method for restoring the database in case of failure, enhancing overall data management.

## Key Stakeholders
- **Database Administrators**: Responsible for managing the database and ensuring data integrity and availability.
- **IT Support Teams**: Use the backup and recovery system to troubleshoot and resolve database issues.
- **Business Analysts**: Rely on consistent data availability to generate reports and insights for business decision-making.

## Process
1. **Database Creation**:
   - Created a sample database named `InventoryDB` with a `Products` table containing product details.
   
2. **Backup Implementation**:
   - Developed a T-SQL script to perform a full backup of the `InventoryDB`.
   - Automated the backup process using SQL Server Agent to ensure regular backups.

3. **Disaster Recovery Testing**:
   - Simulated a database failure by dropping the `Products` table.
   - Restored the database from the backup file and verified that all data was successfully recovered.

4. **Documentation**:
   - Documented the backup and recovery procedures, including the T-SQL scripts and restoration steps.

## Findings
- The automated backup system effectively ensures data availability and integrity.
- Testing the restore process demonstrated that the system can quickly recover from failures, minimizing potential downtime.

## Challenges
- Ensuring that the backup process runs smoothly without interruptions.
- Verifying that the restoration process works as expected after a simulated failure.
- Managing the SQL Server Agent to maintain a consistent backup schedule.
