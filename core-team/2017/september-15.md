# Meeting: Core Team 2017-09-15

### Draft Agenda

- SEPA progessing with CPET metric package
- Discuss tools for potential pilot project
- DARLEQ Taxonomy - outstanding issues
- aquaMetrics package - demo? 
- Sharing code on aquaMetrics github - demo? 
  
#### Proposed date of next meeting  

- Mid-late Nov

### Invitees

CB TF RB IN CP

### Minutes

#### SEPA progessing with metric packages
  
CPET - some progress made, waiting for devleoper time.   
Goal: Will pass details to NRW - CB
Goal: IQI Metrics - share what we have - CB  
    
INNSmetric - NBN Atlas download.    
Goal: will keep NRW informed - TF     
   
Split aquametrics packages into phytobenthosMetrics. And will create a separate invertebrateMetrics package in future.      
Added tests and build checks to phytobenthosMetrics.    
Changes expected to DARLEQ/phytobenthos metrics for TDI5 and DNA work. Will confirm with Steve Juggins/EA and phytobenthos group.  

####  MoU  
MoU - Discussed options. Best place is to progress via UKTAG agreements. Will need something in place if sharing development costs in future.   
  
Goal: MoU - send draft proposal to SEPA - IN  
Goal: Raise with FFTT/UKTAG? CB. Positive response from NIEA. No response from EA as yet.

#### Sharing code on aquaMetrics github - demo?  
Testing and Code coverage - demoed  
Discussed linting, code style, documentation, tests  
Packages - base is faster for spotfire. But packages needed for testing and building. Generally use base but external packages should be okay.   
Documentation - enough documentation to pass CRAN checks but in general will depend on use case of package especially if going to be widely used.    
Protect master branch, commits going into new branch first and then get merged via reviewed pull request.
  
Goal: Add Lintr - TF - (addendum - also agree rules on commit message rules, and creating issues before writing code?)  
Goal: Protect master - use branches for creating pull requests - TF  
Goal: Code review on master branch - TF  
Goal: Check with spotfire team on use of external packages - TF    
Goal: Send Github usernames to TF - IN/CP 
Goal: demo work git flow + testing/checks
  
#### Next meeting

Goal: Late Nov Invite - Fridays / AM - TF



