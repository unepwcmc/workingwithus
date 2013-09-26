Working with Us
=============
# Todays topic:  Estimation and planning  

=============
### Possible future topics  

- Contracting  
- Day to day planning (KANBAN)  
- What happens when it looks like there is no money left in the project  
- what we mean by 'csv template'


### Production and staging environments

While we develop our systems, we make a preview version of the current state of the project available for testing and acceptance. That is what we call the "staging" server. We update this server as we add features, and the process of updating is called "deploying to the staging server". 
When a project reaches release stage, we create another server, which we call "production". That will be the server where the final version of the software will live. Even though the two servers will be very similar, they are completely isolated from one another. 
The staging server may be shut down after launch, or might continue to be utilized alongside the production one as we're developing new features for a live project.
Some key differences between the two environments:
- staging is considered to be unstable. As we develop, we update it frequently. Data will be wiped out and unscheduled maintanence breaks will occur.
- production should be stable. Once data is frozen, it will be regularly backed up. Updates and maintenance breaks should be scheduled.
