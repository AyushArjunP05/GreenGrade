GreenGrade 🌿

Building Sustainability Index --- A Rule-Based Urban Sustainability Platform
GreenGrade is a web-based sustainability assessment prototype designed
to help people looking for rental houses and apartments compare building
sustainability, while helping cities understand building performance and
encouraging property owners to adopt environmentally responsible
practices.

The platform evaluates buildings using transparent, rule-based scoring
across electricity consumption, water usage, neighbourhood green cover,
surrounding air quality, and waste management.
Its purpose is not just to assign a score. GreenGrade helps
prospective tenants make more informed housing choices by comparing
sustainability grades, while helping building owners understand what
they can improve, take practical steps towards sustainability, and track
how those improvements can increase their score.
Project status: Prototype
Scoring approach: Rule-based; no AI/ML scoring
Data: Fictional demonstration records; not connected to live
government databases

📌 Table of Contents
- The Problem
- Our Solution
- Who GreenGrade Helps
- Project Objectives
- How GreenGrade Helps Building
  Owners
- Scoring System
- Features
- Admin Data Entry
- Technology Stack
- Project Structure
- Installation and Setup
- Demo Accounts
- Example Improvement Plan
- Limitations
- Future Scope
- Contributing
- License
  
🌍 The Problem
Buildings contribute to urban environmental pressure through electricity
demand, water consumption, waste generation, and the surrounding built
environment.
However, building owners and residents may not have a simple,
consolidated way to understand their building's sustainability
performance or identify which changes could make the greatest
difference.

Common challenges include:
- High electricity consumption caused by inefficient lighting,
  cooling, and equipment.
- Excessive water use and undetected leakage.
- Insufficient greenery in neighbourhoods.
- Exposure to poor surrounding air quality.
- Improper waste segregation and disposal.
- Limited transparency about environmental performance.
Without understandable performance indicators, it can be difficult to
identify priorities and measure progress. People searching for rental
housing may also have little accessible information to compare the
environmental performance of different buildings before choosing where
to live.

💡 Our Solution
GreenGrade brings several sustainability indicators into one platform
and presents them as a building sustainability score.
The system provides:
1. A consolidated score out of 100.
2. A breakdown of individual sustainability categories.
3. Building search and neighbourhood comparisons.
4. Area-level green-cover and air-quality information.
5. Manual waste-inspection records.
6. Administrative tools for updating reference data and utility
   measurements.
7. A transparent scoring approach that can explain why a score changes.
The current prototype uses predefined rules rather than AI/ML models.
This makes its scoring logic easier to inspect, explain, and test.

👥 Who GreenGrade Helps
1. People looking to rent houses and apartments
Prospective tenants can compare building sustainability grades and
category-level details alongside other important factors such as rent,
location, and amenities. This gives them another source of information
when deciding where to live. A sustainability grade should inform a
housing decision, not replace checks on affordability, safety, location,
or property condition.
2. Building owners and property managers
Visible, comparable grades can create a constructive incentive for
owners to improve buildings with low sustainability scores. Owners may
be concerned that a low grade could make their property less attractive
to some prospective tenants, especially when renters compare several
properties. That competitive pressure can encourage owners to address
issues such as inefficient electricity use, excessive water consumption,
and poor waste management.
GreenGrade aims to turn this pressure into practical improvement---not
public shaming. Scores should use transparent criteria and reliable
data, and owners should have a fair way to correct inaccurate records
and demonstrate improvements.
3. Municipal authorities
Municipal teams can use consistent assessment data to identify
improvement opportunities and encourage greener urban development,
subject to appropriate validation and governance.
The intended feedback loop
Transparent grades → informed rental choices → incentive for owners to
improve → better building performance → greener neighbourhoods.
This is the intended impact of the platform, not a guaranteed outcome:
rental decisions depend on many factors, and improvements must be
measured and verified
.
🎯 Project Objectives
- Encourage energy-efficient building operation.
- Promote responsible water consumption.
- Make neighbourhood environmental conditions more visible.
- Encourage better waste handling and segregation.
- Help owners prioritise practical sustainability improvements.
- Help rental seekers compare houses and apartments using
  sustainability information.
- Encourage owners to improve low-scoring buildings through
  constructive, transparent competition.
- Support transparent, consistent environmental assessment.
- Provide a foundation for future city-level sustainability
  dashboards.
  
🏢 How GreenGrade Helps Building Owners
GreenGrade is intended to turn sustainability data into practical
recommendations.
1. Improve electricity efficiency
Building owners can investigate ways to reduce electricity consumption
without compromising safety, comfort, or essential services.
Possible actions:
- Replace inefficient lighting with suitable LED lighting.
- Maintain air conditioners and other electrical equipment.
- Improve insulation and reduce unwanted heat gain.
- Use energy-efficient appliances when replacing old equipment.
- Use occupancy-based lighting controls where appropriate.
- Monitor electricity consumption regularly.
- Consider suitable renewable-energy options where feasible.
How this can improve the score: The electricity score is based on
energy performance relative to a reference value for the building type.
Lower energy use for the same built-up floor area can improve the
electricity performance ratio and may increase the corresponding points.

2. Reduce unnecessary water consumption
Possible actions:
- Repair leaking taps, pipes, and flush systems.
- Install water-efficient fixtures where suitable.
- Monitor water meters and investigate unusual increases.
- Use efficient irrigation methods for landscaping.
- Reuse suitable treated wastewater where permitted.
- Educate occupants about avoiding unnecessary water waste.
How this can improve the score: Lower normalised water use relative
to the appropriate reference value can improve the water score.
Water use must be compared using a meaningful unit, such as litres per
person per day for residential buildings or an appropriate unit for
other building types.

3. Support neighbourhood greenery
Possible actions:
- Maintain existing trees and green spaces.
- Plant suitable native species where space and permissions allow.
- Support community gardens and green public spaces.
- Protect existing vegetation during building maintenance.
- Encourage rooftop or vertical greenery where structurally suitable.
How this can improve the score: GreenGrade includes
neighbourhood-level green cover. Individual owners can contribute to
greener surroundings, but their personal score may not increase
immediately from planting alone. The area-level data must be updated
using a consistent, documented method.

4. Support better air quality
Possible actions:
- Maintain vehicles and generators properly.
- Avoid unnecessary idling and open burning.
- Follow applicable construction dust-control requirements.
- Maintain equipment that may release pollutants.
- Support public transport, walking, cycling, and urban greenery.
How this can improve the score: The air-quality component uses the
recorded AQI for the surrounding area. An individual owner cannot
directly control the neighbourhood AQI, and their score should not
change solely because of an unverified claim. Area data must come from a
suitable monitoring source.

5. Improve waste management
Possible actions:
- Separate wet waste, dry recyclables, and other locally required
  waste categories.
- Keep recyclable materials clean and appropriately stored.
- Arrange authorised collection for relevant waste streams.
- Compost suitable organic waste where permitted and properly managed.
- Avoid dumping waste in public spaces or drains.
- Follow municipal waste-handling rules.
- Maintain evidence of collection and corrective actions.
How this can improve the score: The waste component is based on
recorded inspection findings. Verified improvements and the resolution
of previous violations can support a better assessment during subsequent
inspections.
Wet waste should not automatically be treated as biodegradable without
considering the material, contamination, and appropriate processing
method.

📊 Scoring System
GreenGrade uses a proposed prototype score with five categories and a
maximum of 100 points.
  Category                            Maximum points Assessment basis
  Electricity                                     25 Actual energy
  efficiency                                         performance compared
                                                     with a building-type
                                                     reference
  Water efficiency                                20 Normalised water use
                                                     compared with a
                                                     suitable reference
  Neighbourhood green                             20 Recorded percentage
  cover                                              of green cover in the
                                                     relevant area
  Surrounding air                                 20 Recorded Air Quality
  quality                                            Index (AQI)
  Waste management                                15 Recorded
                                                     waste-inspection
                                                     findings
  Total                                  100 Combined
                                                 sustainability score
                                                 
Electricity performance
Annual Energy Performance Index (EPI) can be calculated as:
EPI = Annual electricity consumption (kWh) / Built-up floor area (m²)
For a building with multiple floors:
Built-up floor area = Bottom surface area × Number of floors
This simplified calculation assumes the floors have approximately the
same floor area. Actual floor areas should be used when they differ
substantially.
The electricity performance ratio is:
Electricity ratio = Actual EPI / Reference EPI
A lower ratio generally represents better electricity performance
relative to the selected reference. The scoring engine maps the ratio to
the applicable points.
Water performance
For a residential building:
Daily water use per person = Daily water consumption (litres) / Number of residents
A reference ratio can then be calculated:
Water ratio = Actual normalised water use / Reference normalised water use
Other building types may require different normalisation criteria.
Examples include litres per bed per day for hospitals or litres per
occupied room per day for hotels, depending on the selected methodology.
Neighbourhood green cover
Green-cover points are based on the recorded percentage of green cover
in the relevant neighbourhood or administrative area.
The percentage should use a documented boundary and consistent
observation method. A building owner cannot be assumed to control all
greenery within that boundary.
Air quality
The air-quality component uses a recorded AQI value from a suitable
monitoring station. The station, timestamp, and observation source
should be recorded where available.
AQI can vary with time and location. The selected measurement should be
representative of the area being assessed.
Waste management
Waste points are assigned using recorded inspection categories. The
assessment should be based on documented observations, with follow-up
inspections used to verify corrective action.
Important scoring note
The exact thresholds and weights in this prototype are proposed rules,
not official government standards. Before real-world deployment, they
should be validated against appropriate local regulations, technical
standards, and reliable datasets.
Missing information should be marked as unassessed rather than
automatically treated as perfect performance.

✨ Features
Building exploration
- Search for buildings.
- Filter by building category and area.
- View sustainability scores and category-level details.
- Compare the environmental performance of demonstration buildings.
- Help prospective renters compare sustainability ratings when
  considering houses and apartments.
Neighbourhood context
- View recorded green-cover and air-quality information.
- Review the area data associated with a building.
- Understand which environmental factors are building-level and which
  are area-level.
Waste inspection
- Record manual waste-inspection findings.
- Maintain inspection information for subsequent review.
- Support a documented approach to follow-up and corrective action.
Administrative data management
- Update neighbourhood reference data.
- Record green-cover observation details and air-quality information.
- Maintain an audit trail for data changes.
- Enter building utility measurements where supported by the installed
  version.
Rule-based scoring
- Calculate scores using explicit rules.
- Avoid AI/ML scoring.
- Make the assessment logic inspectable and testable.
Persistent storage
- Store prototype data in SQLite.
- Retain supported records across application restarts.
- 
🛠️ Admin Data Entry
GreenGrade requires appropriate input data for meaningful scoring.
Depending on the implemented version, administrative utility records can
include:
Electricity data
- Building identifier and building category.
- Annual electricity consumption in kWh.
- Bottom surface area in square metres.
- Number of floors.
- Reference EPI for the applicable building category.
- Measurement period and data source.
The reference EPI should be selected from a documented, locally
appropriate reference dataset rather than guessed.
Water data
- Building identifier and building category.
- Water consumption in litres over a defined period.
- Number of residents or another appropriate occupancy measure.
- Applicable reference water-use value and unit.
- Measurement period and source.
The system should compare actual and reference values using consistent
units and comparable time periods.
Area data
- Neighbourhood identifier.
- Green-cover percentage.
- Green-cover observation date and source or method.
- AQI value.
- Monitoring station and observation timestamp.
Waste inspection data
- Building identifier.
- Inspection date.
- Recorded inspection category and observations.
- Evidence or reference information where supported.
- Follow-up status where supported by the implementation.
Data quality matters: Incorrect inputs can produce misleading
scores. Changes should be traceable, and the data collection method
should be consistent.

💻 Technology Stack
  Technology         Purpose
  React              Frontend user interface
  Vite               Frontend development server and build tool
  Node.js            Backend runtime
  Express            Backend API
  SQLite             Local database persistence
  JavaScript / JSX   Application logic and interface
  CSS                Interface styling
  Git and GitHub     Version control and source-code hosting
  
📁 Project Structure
GreenGrade/
├── client/
│   ├── src/
│   │   ├── main.jsx
│   │   └── styles.css
│   ├── package.json
│   └── vite.config.js
├── server/
│   ├── index.js
│   ├── scoring.js
│   └── package.json
├── .gitignore
├── package.json
├── package-lock.json
└── README.md

The exact contents may vary slightly as the project develops.

🔐 Demo Accounts
The prototype provides the following demonstration accounts:
  Role                  Email                          Password
  Citizen               citizen@greengrade.local     demo123
  Municipal inspector   inspector@greengrade.local   demo123
  Admin                 admin@greengrade.local       demo123
These are demonstration credentials only. The prototype's authentication
is not production-secure and must not be used to protect real personal
or government data.

📈 Example Improvement Plan
Imagine a residential building whose electricity score is lower than
expected.
1. Review the recorded electricity consumption and floor area.
2. Confirm that the measurement period and reference EPI are correct.
3. Identify inefficient lighting, cooling, or equipment.
4. Introduce suitable efficiency improvements.
5. Record the new electricity consumption over a comparable period.
6. Recalculate the electricity performance ratio.
7. Review the updated category score.
8. Continue monitoring water use and waste-management practices.
The same process can be followed for water consumption and other
applicable indicators.
A building's overall score may improve when its measured performance
improves. However, the size of the improvement depends on the scoring
thresholds, the category weights, and the quality of the input data.
Some components, such as neighbourhood AQI and green cover, depend on
area-level conditions rather than the actions of one owner.

⚠️ Limitations
- All demonstration building records are fictional.
- The prototype is not connected to live government systems.
- Scoring weights and thresholds require local validation.
- Environmental results depend on input-data quality and measurement
  consistency.
- Neighbourhood-level conditions cannot be attributed entirely to an
  individual building owner.
- Manual waste inspections require reliable procedures and
  documentation.
- Demo authentication is intentionally simple and is not
  production-secure.
- The prototype should not be used as a legal compliance certificate
  or official environmental rating.
- A sustainability score alone cannot determine whether a rental
  property is the best choice; rent, location, safety, accessibility,
  and property condition also matter.
- Low grades should be presented with transparent supporting
  information and a way to challenge incorrect data, so the platform
  encourages improvement rather than unfairly damaging a property's
  reputation.
  
Before production use, the platform would need secure authentication,
server-side role-based authorization, stronger validation, backups,
verified data integrations, priv
