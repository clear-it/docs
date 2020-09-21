# Methodology & Technology

## Methodology

 - Volunteers will gather data on what the general requirements for eligibility are on a state by state basis.
 - This data will be accessible via a REST or GraphQL api (see [the Backend repo](https://github.com/clear-it/backend) for specifics).
 - A simple step-form application will allow users to determine whether they are likely to be eligible for expungement to their criminal records (see [the Frontend repo](https://github.com/clear-it/backend) for specifics).

## Suggested Flow

 1. Splash Page / Select State
 2. Select Type of Conviction
 3. Select Years since Conviction
 4. Optional Further Criteria
 5. Results

**Why Steps and not one unified form?**
 Easier on mobile, easier to add new ones in based on individual state requirements, easier for the user to cruise through on a public computer without bystanders seeing it.
