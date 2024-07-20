# online-course-registration
![image](https://github.com/user-attachments/assets/2c8b2275-751c-438f-bdef-636d3aa8c261)
# Database Schema

## Department

<table>
  <thead>
    <tr>
      <th>Column</th>
      <th>Data Type</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>department_id</td>
      <td>INTEGER</td>
    </tr>
    <tr>
      <td>department_name</td>
      <td>VARCHAR</td>
    </tr>
    <tr>
      <td>department_code</td>
      <td>VARCHAR</td>
    </tr>
  </tbody>
</table>

## Courses

<table>
  <thead>
    <tr>
      <th>Column</th>
      <th>Data Type</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>course_id</td>
      <td>INTEGER</td>
    </tr>
    <tr>
      <td>course_name</td>
      <td>VARCHAR</td>
    </tr>
    <tr>
      <td>seats</td>
      <td>INTEGER</td>
    </tr>
    <tr>
      <td>fees</td>
      <td>DECIMAL</td>
    </tr>
    <tr>
      <td>department_id</td>
      <td>INTEGER</td>
    </tr>
    <tr>
      <td>instructor_id</td>
      <td>INTEGER</td>
    </tr>
  </tbody>
</table>

## Students Registration

<table>
  <thead>
    <tr>
      <th>Column</th>
      <th>Data Type</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>student_id</td>
      <td>INTEGER</td>
    </tr>
    <tr>
      <td>first_name</td>
      <td>VARCHAR</td>
    </tr>
    <tr>
      <td>last_name</td>
      <td>VARCHAR</td>
    </tr>
    <tr>
      <td>date_of_birth</td>
      <td>DATE</td>
    </tr>
    <tr>
      <td>email</td>
      <td>VARCHAR</td>
    </tr>
    <tr>
      <td>address</td>
      <td>VARCHAR</td>
    </tr>
    <tr>
      <td>course_id</td>
      <td>INTEGER</td>
    </tr>
    <tr>
      <td>registration_id</td>
      <td>INTEGER</td>
    </tr>
    <tr>
      <td>registration_date</td>
      <td>DATE</td>
    </tr>
    <tr>
      <td>instructor_id</td>
      <td>INTEGER</td>
    </tr>
    <tr>
      <td>department_id</td>
      <td>INTEGER</td>
    </tr>
    <tr>
      <td>gender</td>
      <td>VARCHAR</td>
    </tr>
    <tr>
      <td>phone_no</td>
      <td>VARCHAR</td>
    </tr>
  </tbody>
</table>








