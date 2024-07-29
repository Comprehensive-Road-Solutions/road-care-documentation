# Road Care Documentation

## Project Description

**Road-Care** was developed with the aim of helping to solve problems in road infrastructure such as damaged sidewalks, potholes, etc.

## Target Segments

The project defines two target segments: government workers and citizens.

### Government Workers

For the government workers segment, a web application was developed to manage damaged road infrastructure. This web application facilitates:

- Identifying issues in roads, sidewalks, and other infrastructure.
- Assigning and tracking repair tasks.
- View publications and responses from citizens (in read-only mode).

### Citizens

For the citizens segment, a mobile application was developed as a social network where users can:

- Post information about streets with damaged infrastructure.
- Comment on posts made by other citizens.
- Generating reports on the state of infrastructure.

## Application Architecture

### Web Service
The web service is developed to contain all the business logic, that is, it will contain the operations that will be carried out by both government workers and citizens, which will be integrated with the web and mobile application.

### Mobile Application

The mobile application is designed as a social network for citizens, enabling interaction and collaboration in identifying road issues. Key features include:

- **Posts:** Citizens can post photos, videos and descriptions of damaged infrastructure.
- **Comments:** Citizens can comment on posts to provide additional information.
- **Reports:** Citizens can reports comments or publications false.

### Web Application

The web application is intended for government workers, providing tools to manage road infrastructure. Key features include:

- **Viewing:** Workers can see posts made by citizens in the social network.
- **Management:** Workers can record damaged infrastructure and manage the necessary repairs.
- **Read-Only Mode:** Workers have access to the social network in read-only mode to view posts without direct interaction.

## Summary

**Road-Care** provides a comprehensive solution for identifying and managing road infrastructure issues, facilitating collaboration between citizens and government workers to maintain and improve the road conditions in cities.
