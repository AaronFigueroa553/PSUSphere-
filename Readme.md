# Project Name
<p><span style="font-size:25px;"><b>Students Records Files</b></span></p>

## Short Description
This code customizes the Django admin interface for managing models related to a college system. It defines how the College, Program, Organization, Student, and OrgMember models are displayed, including searchable fields, filters, and custom methods for more intuitive administration.
## List of Features
- <b>CollegeAdmin:</b>
    - Displays college_name, created_at, and updated_at.
    - Searchable by college_name.
    - Filterable by created_at.
- <b>ProgramAdmin:</b>
    - Displays prog_name and associated college.
    - Searchable by prog_name and college_name.
    - Filterable by college.
- <b>OrganizationAdmin:</b>
    - Displays name, college, and description.
    - Searchable by name and description.
    - Filterable by college.
- <b>StudentAdmin:</b>
    - Displays student_id, lastname, firstname, middlename, and associated program.
    - Searchable by lastname and firstname.
- <b>OrgMemberAdmin:</b>
    - Displays student, program, organization, and date_joined.
    - Searchable by student's lastname and firstname.
    - Custom method to show program of a student in OrgMember.

## Authors
- <b>Figueroa, Mark Aaron C.
- Aying, Francis D.</b>
