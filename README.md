# Arbitration Transparency https://arbitrationtransparency.org/
A program, to provide educational assistance about Consumer Arbitration in America, of Make Sure It Happens Inc, a Maryland non-profit and 501(c)(3) EIN 85-3536160 | www.msih.org | ithappens@msih.org | 717-674-4674

Use GitHub [*Issues*](../../issues)  to track project and operational: Bugs, Features, and Tasks

Use GitHub [*Discussions*](../../discussions/categories/general) to discuss project and operational tops: Design, Marketing, Strategy, and Technology

# Purpose
- A Drupal project to provide information about consumer arbitration: rules, process, players, regulations, laws, court cases, and history. 
- A searchable database of company and product arbitration terms: use AI to read agreements for Arbitration Terms.
- A searchable database of claims: allow users to post claims against before submitting them to arbitration.
- A searchable database of outcomes: allow users to share their experience with the arbitration process.
- Advocate for making consumer arbitration transparent: Send emails and letters to businesses and politicians.
- A searchable database of entities that have agreed to make consumer arbitration public.
- Set up fund to pay for legal bills when people break DNA.
- Help people remove DNA from settlements.
- Help people end arbitration agreements.

## Technology
- Frontend: Drupal
- CCS Framework: tailwind
- Backend: MySQL
- Map: Google (autocomplete)
- Email Providers: SendGrid or AWS
- Payment Gateway: Braintree (Paypal)
- Analytics: Facebook, Google
- Unit Testing: xUnit

## Model
- users
- claims
- outcomes
- terms
- Advocate


## Use Cases
- password-less login (use email or sms to validate)
- Create roles for Admin

### Content management
  - menu management
  - add articles
  - tags and categories
  - schedule content
  - create page layouts

### Claims
    - user provides company and location
    - description of the claim
    - support documentation
    - desired outcome
    - Arbitration Rules
    - Name of Arbitor
    - Date of Hearing
    - Date of Outcome
    - Outcome (if public then full if private then satisfied or unsatisfied)
   
# Terms
      - user enters name of company, then search local database, if not found then find site and scrape terms
      - user enters url to company or product web site, then search local database, if not found then scrape terms
      - site if more than 90 days then scrape
      - AI reviews and output json document preset variables (required, pre-arbitration, ....)
      - search results ad filterable should show a table (class action waiver, cost, ...)
     
### Advocate
      - user request email and letter sent to company request arbitration be made public

## Project Plan

### Phase 1 - MVP

- user management: sign up (screen), log in (passwordless), log off
- Landing page (screen)
- Search results screen
- Profile screen
- Footer
- Menu  

### Phase 2

- google autocomplete
- better search capabilities

