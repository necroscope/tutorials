# Database Automation

![logo](image/logo-x.png) &nbsp;&nbsp;&nbsp;[« Back to Previous Section](Database-Automation.md)

## Section 2: Dynamic SQL / incorporate data variable

Inborn within Nexial is the flexibility to construct "things" - more specifically, test data - 
dynamically.  We will have a separate tutorial dedicated to that topic.  For now, we want to
explore the possibility of constructing SQL query dynamically so that:
- our automation can react accordingly to external controls
- our automation can be reusable - like a template - towards multiple similar scenarios
- one automation can integrate with other another automation script by utilizing the same
data variables

Let's see some examples:

#### Example 1: Parameterizing SQL

#### Example 2: Just-in-time WHERE clause construction

#### Example 3: Dynamic SELECT clause 

There's a much more powerful way to generate dynamic SQL using Nexial Expression.  We will cover 
this in a later tutorial.

---

Up next: [SELECT to inspect](Database-Automation-selectinspect.md)

### TODO
2)	Dynamic SQL / incorporate data variable
3)	SELECT to inspect
4)	SELECT to validate
5)	SELECT to CSV / bulk comparison
6)	Query metadata
7)	Flow control through query resultset and metadata
8)	UPDATE database via SQL
9)	Transaction support
10)	Executing multiple SQLs / Execution SQL file
11)	Sentry Expression for database automation 
12)	Bulk generate SQL via "template"
