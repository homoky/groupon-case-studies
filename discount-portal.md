# Discount portal

## Phase 1. - Research

- **Audience Identification**: How will we define and reach our primary consumers?
- **User Case Analysis**: How can we obtain and incorporate user feedback for primary scenarios?
- **Platform Focus**: Should we prioritize a mobile or desktop interface if resources limit us to one?
- **Integration with Existing Products**: If our portal is part of a broader product suite, is it advisable to integrate with a shared authentication system?
- **Standalone Authentication**: For an independent portal, what authentication measures are necessary for the initial release?
- **Audience Acquisition Responsibility**: Which team member will take the lead on audience acquisition strategies?
- **Monetization Strategy**: Through what mechanisms will the portal generate profits?
- **Traffic Projections**: What are our projections for user traffic volume?
- **Competitive Analysis**: Which competitors should we benchmark against, and what are their standout features?
- **Business Model Focus**: With a business partner securing our initial deals, to what extent should we develop the business functionalities in version 1?
- **Content Diversification**: What additional content types will we create to engage our audience?
- **Data Privacy Compliance**: How will we ensure compliance with data protection laws, and under whose authority are we operating?
- **Customer Support Standards**: What standards of customer support will we commit to, and through what means will we deliver it?
- **Future Development Roadmap**: What are our plans for the portal's evolution post-launch, including feature updates and new version releases?
- **Brand Evaluation**: Does a brand already exist, and if so, how will it influence our project?
- **Brand Identity Consideration**: Is there an established brand identity that we need to align with?
- **Supplier Components**: Will we be working with any pre-existing components from contractor?
- **Team Experience**: What is the level of experience among the team members?
- **Project Budget**: What is the total budget allocated for delivery?
- **Quality and Success Decision-making**: Who will be in charge of deciding the quality and success criteria for the project?
- **Expectation Awareness**: Are there any specific expectations I should be aware of in advance?

## Phase 2. - Setting up technical solution

### v1

- Database:
  - Postgres / MySQL
  - ORM for database - Prisma
- Backend
  - GraphQL
  - typescript
  - Nexus
- Frontend
  - React (Next.js)
  - Tailwind UI
  - Storybook
- Backoffice
  - Interval.com
- Hosting - deployment setup
  - Render / Digital Ocean App Platform
- Payment method
  - Stripe (also for creating issues)
- Transactions email
  - Mailgun or other solution
- Code storage, issue tracker
  - Github
  - Github projects

### v2

- faster CI for deployment
- E2E tests for API
- E2E tests for forms on UI

## Phase 3. - Finalizing user stories

From the initial user stories that we've gathered and received feedback on, we will compile a summary of what is absolutely essential for the first version (V1) of the product. This will help us determine what features must be included and what can be deferred, allowing us to prioritize the development tasks effectively. Each of these prioritized user stories will then be translated into separate issues on GitHub, with clear labels and milestones for tracking. This approach ensures that our development focus is aligned with user needs and that we have a structured plan for addressing and implementing each feature systematically.

## Phase 4. - Creating database model

Once we have all the essential questions answered, understand the user stories, expectations, and have some traffic estimates, we will design a database model. This model will ideally mirror the future GraphQL schemas on a one-to-one basis, ensuring that our backend architecture aligns perfectly with our API layer and front-end requirements. This foresight in planning will facilitate smoother development and scalability as the project grows.

## Phase 5. - Making estimations (end of the first week)

Given the comprehensive setup we have in place, from the technical solutions outlined in Phase 2 to the detailed planning in Phase 3 and 4, we are now in a position to prepare Estimated Time of Arrival (ETA) for each issue.

This process will involve assessing the complexity of the issues, the dependencies between them, and the individual capabilities of our development team members.

By doing so, we can establish a realistic timeline for the completion of tasks, ensuring that the project milestones are met and that the development process progresses in a controlled and predictable manner. These ETAs will be critical in managing expectations, both internally and externally, and will serve as a key component in our overall project management strategy.

## Phase 6. - Development

The development process will be segmented into three dedicated teams, each focusing on different aspects of the project. The backend team, backoffice team, and UI team will work in parallel to ensure comprehensive coverage of all system components.

**Backoffice Team**: Their primary objective will be to create a robust management system. This will include tools for managing offers, handling customer support queries, and providing the business department with basic financial operational insights. The functionality they develop will be crucial for the day-to-day administration of the platform.

**UI Team**: This group will be tasked with developing the frontend, integrating authentication services, and collaborating with the UX designer to define a suite of common components for the Storybook, ensuring design consistency across the platform. They will also implement a monitoring tool like Smartlook to track user interactions, which will inform future enhancements based on real-world usage.

**Backend Team**: They will focus on preparing use cases for the various mutations and queries that will be required by the frontend and backoffice, translating these needs into the database model. This ensures that the data structure is optimized for the required operations and is scalable for future needs.

Development will progress by identifying and tackling the next three most critical issues for each team. The first phase will see the backend laying the groundwork, UI connecting with the backend, and UX fine-tuning, while simultaneously, the backoffice infrastructure is established.

Should the backoffice team have additional capacity, they will contribute to writing automated tests for the backend, maximizing resource utilization and ensuring a robust, well-tested application. This approach not only accelerates development but also fosters cross-functional understanding and collaboration within the teams.

## Phase 7. - Quality Assurance

Q&A team will help from second week to check validity of user cases and will provide feedback from user perspective. Team will also check the whole selling flow and will integrate support team to check out we are ready to handle edge cases.

## Phase x - After launch

In addition to the above strategies, it is critical to continually verify whether we are meeting the expectations set forth at the project's inception. This involves a cyclical process of evaluation and adjustment:

- **Expectation Alignment**: Regularly review project goals and deliverables against stakeholder expectations, ensuring that every development sprint is moving us closer to fulfilling these criteria.
- **Feature Implementation for Business Needs**: Actively seek input from the business team to understand their needs, which could involve adding specific functionalities that the users or support team desire. By incorporating these features, we can enhance the platform's value proposition and directly contribute to fulfilling business objectives.
- **Analytics and Feedback Synergy**: Utilize the integrated analytics platform to validate if the user experience aligns with expectations. Combine this data with direct user feedback to paint a comprehensive picture of user satisfaction and areas for improvement.
- **Iterative Development**: Employ an agile approach to iterate on the product based on feedback and analytics, ensuring that every update is an opportunity to meet and exceed expectations.
- **Business Involvement**: Ensure that the business department is not just a passive recipient of updates but is actively involved in the feature validation process, confirming that the development aligns with business strategies and user demands.

By maintaining a focus on expectations and being ready to pivot where necessary, we ensure that the product evolves in a way that consistently delivers value to both the business and its customers.
