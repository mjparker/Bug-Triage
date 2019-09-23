# Bug Severity Guidelines

## Severity Levels

### Sev 1: Critical - The bug stops the product and no workaround is possible
- Critical functionality or critical data is affected and there is no known workaround. 
- All performance and security bugs should be considered critical and their severity reduced as we become aware of their scope.
- This severity should also be used when the bug prevents further testing of the feature or product. 

### Sev 2: Major - The bug can stop the product but only if some additional circumstance is met
- If a bug breaks existing functionality and has a workaround that is not obvious or is difficult, high severity should be used.

### Sev 3: Minor - The bug breaks a minor part of the product
- Features that work as designed, but that have a design that breaks a user’s mental model of how a feature ought to work, might qualify as Minor, but more often qualify as Trivial.

### Sev 4: Trivial - The bug is cosmetic or an irritation
- Command and easy to identify
- No real impact on the functionality of the application

## Bug Fix Timeline (sometimes referred to as an internal SLA)
- Sev 1 - requires immediate work by any/all teams that necessary to restore functionality. 
- Sev 2 - should fixed within a team's current sprint.
- Sev 3 - assessed by the team and fixed as capacity allows.
- Sev 4 - may be fixed if a developer happens to be working within that code. 


## Severity vs. Priority
Note that "severity" and "priority" are distinctly different. 

ISTQB defines severity as "the degree of impact that a defect has on the development or operation of a component or system". Priority is defined as "the level of (business) importance assigned to an item, e.g. defect". So while a bug may be assigned a severity of "Minor", the business case for fixing the bug may require an immediate fix. 

In other words, "severity" denotes the technical urgency of the issue, while "priority" represents urgency as it relates to the business and/or its customers.