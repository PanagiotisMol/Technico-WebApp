## Project general description
A Renovation Contractor Agency, Technico, within the framework of its operation, needs a
web application that will enable the employees - managers of this platform to access
information concerning customers and repairs. It will also enable its customers to oversee
the progress of repair/renovation work on their property.

### User roles
- Admin 
- Property Owner

## Domain Models

### Owner model
- VAT number 
- Name
- Surname
- Address
- Phone number• E-mail (used as Username )
- password
- type of user

### Property model 
- Α Property Identification Number, which coincides with the corresponding
number of E9 and will uniquely characterize the property,
- Property address,
- Year of construction,
- Type of property (Detached house, Maisonet, Apartment building), (Note: this
field is now removed by the owner
- VAT number of its owner.
### Repair model
- Date (datetime) of the scheduled repair
- Type of repair (Painting, Insulation, Frames, plumbing, electrical work)
- Repair description as a free-text field for the work to be done (e.g., installation
of a solar water heater)
- Repair address
- Status of the repair (Pending, In progress, Complete - default is the pending
status)
- Cost of repair
- Owner for whom the repair is made

## Non-functional requirements
1. ASP.NET Core
2. Use EF Core
3. Use DI and Clean Architecture
4. Use Coding Conventions and architectural standards
