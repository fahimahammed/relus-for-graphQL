﻿# 15 Rules for GraphQL design 
## Apollo-Graphql

**Rule-1:** Always start with a high-level view of the objects and their relationships before you deal with specific fields.

**Rule-2:** Never expose implementation details in your API design.

**Rule-3:** Design your API around your business domain.

**Rule-4:** It's easier to add fields than to remove them.

**Rule-5:** Group Closely related fields together into sub-objects

**Rule-6:** Always check if a list should be paginated

**Rule-7:** Always use Object regerences intesd of ID fields

**Rule-8:** Choose field names based on what makes sense, Not the implementation.

**Rule-9:** use Enums for fields that can only take a specific set of values

**Rule-10:** Your API should provide business logic, Not just data.

**Rule-11:** Write separate mutaions for separate logical actions on a Resource.

**Rule-12:** For relationship Mutations consider operating on multiple elements

**Rule-13:** Prefix Mutation names with the object for alphabetical grouping.

**Rule-14:** Structure mutation inputs to reduce duplication.

**Rule-15:** Mutations should provide user/business level errors.
