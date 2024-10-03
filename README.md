# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

Job Board Portal Application

1. Authentication Component:

   - Implement login and registration forms using Formik or React Hook Form.
   - Handle role-based authentication (Job Seeker, Employer, Admin).

2. Job Listings Component:

   - Display a list of jobs posted by employers.
   - Enable job seekers to filter jobs based on location, skills, experience, etc.

3. Job Application Form:

   - Allow job seekers to apply for jobs by attaching their resume and writing a cover letter.

4. Employer Dashboard:

   - Provide a portal for employers to post new jobs and manage existing listings.
   - List all applications received for specific job posts.

5. Admin Dashboard:

   - Display platform statistics (number of jobs, number of applicants).
   - Show reports for job activities and user accounts.

6. Notifications and Alerts:

   - Notify job seekers when new jobs matching their skills are posted.
   - Notify employers when an application is received.

DB Design :

users :

1.  Job seeker

    - Profile photo:
    - Name, Phone number, Email:
    - About:
    - Position:
    - Education:
    - Location, City:
    - Resume:
    - Experience, Skills:
    - User ID:

2.  For Recruiters:

    - Profile photo:
    - Name, Phone number, Email:
    - About:
    - Position:
    - Education:
    - Location, City:
    - User ID:
    - Company Name
    - Image(Post image)

3.  Job Details:

    - Company Name:
    - Apply link or Email id
    - Salary
    - location
    - openings
    - Job Title/Position:
    - Job Description:
    - Job Type: Full-time, part-time, contract, etc.
    - Experience Level: Specifies if the role is for entry-level, mid-level, or senior-level candidates.
    - Skills Required: Any specific skills or qualifications needed for the job.

Developmeny :

1. Frontend :

   - Initial Layout

     - Header
     - Side bar
     - Main content
     - Footer

1) - Pages

     - Register / Login Page

       - Register
       - Header
         - Logo
         - Login Link
       - Register Form

         - Full Name
         - Email Id
         - Password
         - confirm password
         - mobile number
         - work status
           - Experienced
           - Fresher

       - Login Form
         - Header
           - Logo
           - Login
           - Register
           - For Employees
         - Login Form
           - Email ID
           - Password

- Header

  - Home
  - Jobs
  - My Activity
    - My applications
  - Notifications
  - Light mode / dark mode
  - Profile
    - User name
    - position
    - view profile

- sign in or sign up
  - seperate page for each
