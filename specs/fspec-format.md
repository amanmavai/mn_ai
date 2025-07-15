# FSPEC (Feature Specification) Format

## Core Principles
- **Intent over Implementation** - Focus on what and why, not how
- **Context-Complete** - All necessary context in one place
- **Action-Oriented** - Clear behavioral expectations
- **Constraint-Explicit** - Limitations and requirements stated upfront

## Format Structure


# FSPEC: [Feature Name]

## INTENT
[Single sentence describing the user value/business purpose]

## BEHAVIOR
### GIVEN [Context/State]
### WHEN [Action/Trigger]  
### THEN [Expected Outcome]

## CONSTRAINTS
- Technical: [Performance, dependencies, compatibility]
- Business: [Rules, validations, edge cases]
- UX: [Interaction patterns, accessibility]

## CONTEXT
- Existing: [Current relevant code/features]
- Dependencies: [What this relies on]
- Impact: [What this affects]

## ACCEPTANCE
- [ ] [Specific testable criteria]
- [ ] [Specific testable criteria]


## Example Implementation


# FSPEC: User Authentication with JWT

## INTENT
Enable secure user login/logout to protect application resources

## BEHAVIOR
### GIVEN user has valid credentials
### WHEN user submits login form
### THEN system generates JWT token and redirects to dashboard

### GIVEN user has expired/invalid token  
### WHEN user accesses protected route
### THEN system redirects to login page

## CONSTRAINTS
- Technical: JWT expires in 24h, bcrypt for passwords, Redis for sessions
- Business: Max 3 failed attempts = 15min lockout
- UX: Clear error messages, remember last username

## CONTEXT
- Existing: User model in models/User.js:15, auth middleware in middleware/auth.js:8
- Dependencies: bcrypt, jsonwebtoken, express-session
- Impact: All protected routes, user registration flow

## ACCEPTANCE
- [ ] Valid credentials generate working JWT
- [ ] Invalid credentials show error message
- [ ] Expired tokens redirect to login
- [ ] Account lockout after 3 failures
- [ ] Logout clears session completely
  

## Why This Format Works for AI Implementation

- **AI-friendly structure** with clear sections
- **Behavioral clarity** through GIVEN/WHEN/THEN
- **Complete context** including file references  
- **Testable outcomes** via acceptance criteria
- **Constraint awareness** for quality implementation

The format balances simplicity with completeness, giving AI models enough context to implement confidently while remaining concise and actionable.