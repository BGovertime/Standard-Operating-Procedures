Standard-Operating-Procedures (SOPs): Universal Workflow

1.0 Introduction and Core Principles
Standard operating procedures document(Standard Operating Procedure - SOP) This version is prepared to establish a standardized framework under the name..."Universal Workflow"The strategic objective is to create clear operational guidelines, ensuring process repeatability across all projects and guaranteeing real-time data updates. Following these guidelines will reduce complexity, improve efficiency, and enhance consistency in collaboration throughout the organization.
The fundamental principles of Universal Workflow are based on five key concepts that work together systematically:
Workflow + Calendar Loop:Integrating systematic workflows with clear and predictable schedules creates a consistent workflow.
Tool Standardization:Clearly prioritizing and assigning roles to the tools used in each step is crucial for reducing redundancy and maximizing efficiency.
Real-time Updates:Using automation to link and update documents ensures that information is accurate and up-to-date without the need for manual action.
Reusable Framework:Designing a standardized framework that can be applied to all projects and repeated annually to maintain continuity and reduce the burden of starting over.
Data Integrity and Ethics: Prioritizing the accuracy and completeness of data is paramount, coupled with establishing ethical guidelines for its use to prevent misuse.
The key to this systematic approach begins with clearly defining the tools and roles, which forms the foundation for building effective processes in the subsequent steps.
2.0 Tool Hierarchy and Roles
Tool standardization is a key element in reducing workflow complexity. Prioritizing tools helps teams clearly understand the role and scope of each application, resulting in the most efficient and objective-aligned tool selection at each stage of the workflow.
The table below categorizes the tools according to their priority and primary roles within the Universal Workflow:
number
Tools and their primary roles.
1
VS Code:It is the primary Integrated Development Environment (IDE) for development, used for documenting code and manuals, and is a key tool in the analysis and prototyping phase.
2
GitHub:It serves as a central repository for storing files, controls version control of all files, and forms the foundation for defining standard workflows for the entire system.
3
Week:It is used as living documentation for user manuals and quick access to information, acting as a mirror image of the main document.
4
Note:Used for quickly capturing short ideas or to-do lists (Quick Capture) to prevent information from being lost during work.
5
Docs:It is used to prepare final documents such as research summaries, project reports, and complete manuals. It serves as the primary source of information (Source of Truth) for the project.
6
Cloud (OneDrive/Google Drive):It is a recommended tool for storing source files and supplementary information, with links to the main document.Docs
7
Sources of information and social media:Used for publishing results externally once the project is complete.

These tools will be applied at each stage of a systematically defined work cycle to ensure smooth and continuous operations.
3.0 The Workflow Loop
The "Workflow Loop" concept is a cyclical process of six sequential steps designed to guide a project from initial conception to final presentation. This framework ensures that every activity is systematically recorded, stored, and version-controlled using tools defined at each stage.
The 6 steps ofWorkflow Loop together with:
Analyze and create content.
activity:It is the initial step in drafting and prototyping a project, whether it be code, documentation, or a project plan.
tool: VS CodeThis will be used as the primary space for developing and writing content.NoteUsed for jotting down ideas that come to mind quickly.
Save and control versions.
activity:Once the draft content has progressed to a certain level, the changes are saved to the version control system. A new branch is created for each task to avoid affecting the main version.
tool: GitHubIt is the primary tool for committing all changes.
Explain and link the information.
activity:Create sub-guides and add queries for data referencing so that relevant parties can study and understand the details of the work.
tool: WeekThis will be updated at this stage, mostly as a result of automated systems connected to...GitHub
Summarize and archive.
activity:Gather all the information to create a complete report or manual, and store the original files or related supplementary data in a secure location.
tool: DocsUsed to create the final report.Cloud(OneDrive/Google Drive) is used to store the original file.
Share and present.
activity:Communicate progress, summarize results, or present project outcomes to the team or stakeholders, and release them to the public upon approval.
tool: Zoom and EmailThe first section is used for internal team meetings and summaries, while the social section is for sharing externally.
Loop
activity:This process is continuously iterative, with daily summaries and new plans, and an annual review of all repositories to update and start a new cycle.
tool:Use all the tools in the system to support this loop.
These work processes are controlled and driven by clear timeframes, whether at the daily, monthly, or yearly level, to ensure discipline and continuity in operations.
4.0 Operational Cadence (Calendar Loops)
A "Calendar Loop" is a time-setting mechanism that helps organize workflow loops to occur regularly and predictably. Having a clear workflow rhythm is an application of this principle."Workflow + Calendar Loop"Let's put it into practice, which is key to building discipline, continuity, and enabling the team to plan and execute tasks with maximum efficiency.
4.2 Cycle Operational Timing
4.2.1 Daily Calendar Loop
Today's work schedule is designed to divide activities to align with energy and creativity throughout the day.
time
activity
tool
09:00 – 12:00
Analyze/write code/record ideas
VS Code, Note
12:00 – 13:00
Take a break/Review
—
13:00 – 15:00
Commit + Update Wiki/Docs
GitHub, Week, Docs
20:00 – 21:00
Daily task summary
Docs, Note
21:00 – 22:00
Plan for the next day + Meeting
Email, Zoom

4.2.2 Monthly Loop
Every month, there are activities to review and maintain the system's operations to ensure they are always up-to-date:
Review the overview of the Repository andWeek
Update information and documents that may be outdated.
4.2.3 Annual Loop
Throughout the year, all work processes are reviewed and improved in preparation for the following year:
examine (Audit)The efficiency of the entire system and work processes.
amend Workflow Based on the feedback and lessons learned.
Begin a new work cycle.
The efficiency of this clearly defined workflow is further enhanced by automation that intelligently connects various tools.
5.0 System Integration and Automation
System integration(System Integration)This is the key to ensuring that Universal Workflow operates smoothly and efficiently. A well-designed automation system helps reduce manual steps, minimizes human error, and ensures real-time data consistency across the entire system.
The key automated operating mechanisms are as follows:
Automatic document synchronization. GitHub Actions
Working conditions: GitHub ActionsThis will run automatically every time code or documentation is committed on a branch.mainOr when it is manually triggered via the Workflow screen.
process:The system will copy all files from the folder.docs/(Primary source of information) Go toWeek repository (.wiki) automatically, then commit and push the changes to.Week
result:This mechanism causes...WeekUpdated as scheduled.DocsEvery time a commit is made. by DocsIt serves as a primary source of truth.WeekIt acts as a mirror for quick referencing, reducing the burden of manually copying files and ensuring that all versions of the document are always consistent.
Connecting communication and meetings.
process: Email and CalendarIt is used to automatically send daily work summaries and to schedule team meetings.Zoom
result: ZoomIt has been designated as the primary tool for the Team Sync meeting between 9 PM and 10 PM to plan for the following day.
Data storage linking
process: CloudSync (via OneDrive/Google Drive) is used to back up and store the original files and additional data.
result:These files can be linked to documents within...DocsThis allows for direct access, making it convenient and organized to access the source data.
For these automated systems to function fully and to their maximum benefit, clear standards for document and data structure are necessary, which will be explained in the next section.
6.0 Documentation Standards and Data Ethics
The success of a Universal Workflow depends not only on the tools and processes but also on the quality and consistency of the data. Having clear documentation standards and a code of ethics is essential. Standardized structures and templates help maintain data consistency throughout the project, while the code of ethics builds trust and prevents data misuse.
6.2 Standards and principles
6.2.1 Standard Folder Structure and Templates
For the sake of organization and ease of searching, a standard folder structure has been established.repository/docs/, week/, queries/In addition, standard templates are provided to prevent the omission of important information and ensure consistency across all documents.
Example: Checklist Template (checklist-template.md)
Project Checklist
Basic information
[ ] Project ID
[ ] Project Title
[ ] Author/Owner
[ ] Version
[ ] Last Updated
Main content
[ ] Overview (Project Overview)
[ ] Objectives (Purpose)
[ ] Key Findings (Main Analysis Results)
[ ] Next Steps (Next steps plan)
Additional information
[ ] References (Sources/Links)
[ ] Queries (data retrieval commands)
[ ] Attachments (Original file/Cloud link)
Inspection
[ ] Commit to GitHub
[ ] Sync to Wiki
[ ] Reviewed by Team
6.2.2 User Guide Standards
All manuals must be created according to standard structures.GuideBlueprintIn order to have complete and consistent metadata throughout, which includes:id, title, description, version, author, last_updated: date, commands, and ethics_banner
6.2.3 Principles and ethics in data usage.
To foster accountability and trust in data management, all users must adhere to the following:"Principles of Data Use"The following five points:
Accuracy:Use the information as recorded in the manual and do not modify it without verification.
Transparency:Always indicate the source of information and provide references.
Responsibility:Users are responsible for the consequences of using the data.
Safety:Do not use this information to violate the rights of, misrepresent, or harm others.
Ethics:Use data for development, learning, and innovation, not for destruction.
In addition, every manual must include..."Ethics & Safety Banner"It is always displayed before the main content as a reminder to users.
⚠ Ethics & Safety Notice
The information in this guide is part of research and development.
All users must adhere to the following principles:
Use the information accurately and transparently.
Take responsibility for the consequences.
Do not use this information for human rights violations or harm.
Respect the ethics and safety of all parties.
By accessing and using this information, the user agrees to these terms.
Applications in Workflow: fee ethics_bannerThis must be included in the metadata of every guide, and the automated system will always display this label before the main content when syncing.Docs and Week
--------------------------------------------------------------------------------
Adhering to all standards and principles outlined in this SOP will enable the team to operate within the established framework.Universal WorkflowEfficiency, transparency, and shared accountability are fundamental to the success of all projects.



# Contributor Covenant 3.0 Code of Conduct

## Our Pledge

We pledge to make our community welcoming, safe, and equitable for all.

We are committed to fostering an environment that respects and promotes the dignity, rights, and contributions of all individuals, regardless of characteristics including race, ethnicity, caste, color, age, physical characteristics, neurodiversity, disability, sex or gender, gender identity or expression, sexual orientation, language, philosophy or religion, national or social origin, socio-economic position, level of education, or other status. The same privileges of participation are extended to everyone who participates in good faith and in accordance with this Covenant.


## Encouraged Behaviors

While acknowledging differences in social norms, we all strive to meet our community's expectations for positive behavior. We also understand that our words and actions may be interpreted differently than we intend based on culture, background, or native language.

With these considerations in mind, we agree to behave mindfully toward each other and act in ways that center our shared values, including:

1. Respecting the **purpose of our community**, our activities, and our ways of gathering.
2. Engaging **kindly and honestly** with others.
3. Respecting **different viewpoints** and experiences.
4. **Taking responsibility** for our actions and contributions.
5. Gracefully giving and accepting **constructive feedback**.
6. Committing to **repairing harm** when it occurs.
7. Behaving in other ways that promote and sustain the **well-being of our community**.


## Restricted Behaviors

We agree to restrict the following behaviors in our community. Instances, threats, and promotion of these behaviors are violations of this Code of Conduct.

1. **Harassment.** Violating explicitly expressed boundaries or engaging in unnecessary personal attention after any clear request to stop.
2. **Character attacks.** Making insulting, demeaning, or pejorative comments directed at a community member or group of people.
3. **Stereotyping or discrimination.** Characterizing anyone’s personality or behavior on the basis of immutable identities or traits.
4. **Sexualization.** Behaving in a way that would generally be considered inappropriately intimate in the context or purpose of the community.
5. **Violating confidentiality**. Sharing or acting on someone's personal or private information without their permission.
6. **Endangerment.** Causing, encouraging, or threatening violence or other harm toward any person or group.
7. Behaving in other ways that **threaten the well-being** of our community.

### Other Restrictions

1. **Misleading identity.** Impersonating someone else for any reason, or pretending to be someone else to evade enforcement actions.
2. **Failing to credit sources.** Not properly crediting the sources of content you contribute.
3. **Promotional materials**. Sharing marketing or other commercial content in a way that is outside the norms of the community.
4. **Irresponsible communication.** Failing to responsibly present content which includes, links or describes any other restricted behaviors.


## Reporting an Issue

Tensions can occur between community members even when they are trying their best to collaborate. Not every conflict represents a code of conduct violation, and this Code of Conduct reinforces encouraged behaviors and norms that can help avoid conflicts and minimize harm.

When an incident does occur, it is important to report it promptly. To report a possible violation, **[NOTE: describe your means of reporting here.]**

Community Moderators take reports of violations seriously and will make every effort to respond in a timely manner. They will investigate all reports of code of conduct violations, reviewing messages, logs, and recordings, or interviewing witnesses and other participants. Community Moderators will keep investigation and enforcement actions as transparent as possible while prioritizing safety and confidentiality. In order to honor these values, enforcement actions are carried out in private with the involved parties, but communicating to the whole community may be part of a mutually agreed upon resolution.


## Addressing and Repairing Harm

**[NOTE: The remedies and repairs outlined below are suggestions based on best practices in code of conduct enforcement. If your community has its own established enforcement process, be sure to edit this section to describe your own policies.]**

If an investigation by the Community Moderators finds that this Code of Conduct has been violated, the following enforcement ladder may be used to determine how best to repair harm, based on the incident's impact on the individuals involved and the community as a whole. Depending on the severity of a violation, lower rungs on the ladder may be skipped.

1) Warning
   1) Event: A violation involving a single incident or series of incidents.
   2) Consequence: A private, written warning from the Community Moderators.
   3) Repair: Examples of repair include a private written apology, acknowledgement of responsibility, and seeking clarification on expectations.
2) Temporarily Limited Activities
   1) Event: A repeated incidence of a violation that previously resulted in a warning, or the first incidence of a more serious violation.
   2) Consequence: A private, written warning with a time-limited cooldown period designed to underscore the seriousness of the situation and give the community members involved time to process the incident. The cooldown period may be limited to particular communication channels or interactions with particular community members.
   3) Repair: Examples of repair may include making an apology, using the cooldown period to reflect on actions and impact, and being thoughtful about re-entering community spaces after the period is over.
3) Temporary Suspension
   1) Event: A pattern of repeated violation which the Community Moderators have tried to address with warnings, or a single serious violation.
   2) Consequence: A private written warning with conditions for return from suspension. In general, temporary suspensions give the person being suspended time to reflect upon their behavior and possible corrective actions.
   3) Repair: Examples of repair include respecting the spirit of the suspension, meeting the specified conditions for return, and being thoughtful about how to reintegrate with the community when the suspension is lifted.
4) Permanent Ban
   1) Event: A pattern of repeated code of conduct violations that other steps on the ladder have failed to resolve, or a violation so serious that the Community Moderators determine there is no way to keep the community safe with this person as a member.
   2) Consequence: Access to all community spaces, tools, and communication channels is removed. In general, permanent bans should be rarely used, should have strong reasoning behind them, and should only be resorted to if working through other remedies has failed to change the behavior.
   3) Repair: There is no possible repair in cases of this severity.

This enforcement ladder is intended as a guideline. It does not limit the ability of Community Managers to use their discretion and judgment, in keeping with the best interests of our community.


## Scope

This Code of Conduct applies within all community spaces, and also applies when an individual is officially representing the community in public or other spaces. Examples of representing our community include using an official email address, posting via an official social media account, or acting as an appointed representative at an online or offline event.


## Attribution

This Code of Conduct is adapted from the Contributor Covenant, version 3.0, permanently available at [https://www.contributor-covenant.org/version/3/0/](https://www.contributor-covenant.org/version/3/0/).

Contributor Covenant is stewarded by the Organization for Ethical Source and licensed under CC BY-SA 4.0. To view a copy of this license, visit [https://creativecommons.org/licenses/by-sa/4.0/](https://creativecommons.org/licenses/by-sa/4.0/)

For answers to common questions about Contributor Covenant, see the FAQ at [https://www.contributor-covenant.org/faq](https://www.contributor-covenant.org/faq). Translations are provided at [https://www.contributor-covenant.org/translations](https://www.contributor-covenant.org/translations). Additional enforcement and community guideline resources can be found at [https://www.contributor-covenant.org/resources](https://www.contributor-covenant.org/resources). The enforcement ladder was inspired by the work of [Mozilla’s code of conduct team](https://github.com/mozilla/inclusion).

