## Boundary for analysis and accounting

Scope can be thought of as a boundary for analysis and accounting, mostly used for sets of economic events, commitments, and intents.  A scope is an agent of some kind.  See also [Agent concepts](agents.md).

The scope is where work is done, where processes live, where value is created and exchanged. Economic events, commitments and intents can reference an organization, person, or ecological agent as an entity that defines their scope.

It is not required that events, commitments, or intents designate a scope.  In fact, sometimes the scope is the same as the provider or recipient agent.  Or sometimes there is no useful scope.

For functions that require traversing value flows, often the value flow will cross from one scope to another.  For example, perhaps another network or organization makes a component that you consume when making your product.  When this happens, there are some options.

* Standing agreements can govern what happens.
* A conversation for action might be required to determine what should occur for the specific instance.

## Accounting

Accounting is usually done for a bounded scope. Where a computer system supports one enterprise, this is simple.  When a computer system supports many organizations or there is a distributed network of economic activity, it is useful to be able to segregate the accounting using scope.  It basically enables multi-party accounting in a networked scenario.

## Planning

Sometimes a generic recipe will cross scope boundaries for particular agents. For example one agent could produce a resource that consumes a component made by another agent.  In this case, can the first agent schedule the production of the component by the second agent?  Possibly yes, if there are agreements in place for that, and the first agent has verified that inventory does not already exist.  Or possibly, based again on agreements, the first agent can assume the second agent will provide the component, with the second agent taking responsibility for checking if it is onhand, and if not, scheduling it for production.

## Distributing Incoming Resources

Some organizations distribute income backwards on value flows, based on people's contributions to the resources that generated the income.  When traversing the value chain, it is useful to know when the traversal has crossed a scope boundary, because it is possible that the rules for distributing the incoming resources will change for a different scope.  If the rules change or the rules are unknown, the income can be passed on to the other scope for them to distribute.

Note that income does not need to be money and can include distributing the output of a process to the contributors, like when a community farm distributes food to its contributors.

## Scoping Agents

Often the scope can be determined by already recorded agents, such as provider, receiver, subject, object.  But in other cases, for example when an organization is keeping track of activity or relationships between members, an explicit scoping agent is needed.  Implementations that use the scope concept may want to always record the scope of relevant entities, even when they can be implied.
