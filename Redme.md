<h1>Overview</h1>

This project is to build an Access Management System which will be similar to Access Management in Snowflake. <br>

<h1>Process</h1>

<h2>Requirements</h2>
<ul>
    <li>There will be some pre-defined roles which will have privileges specific to those roles</li>
    <li>These pre-defined roles will have a hierarchy in place.</li>
</ul>

<h3>Roles</h3>
<ul>
    <li>AccountSupervisor</li>
    <li>SecuritySupervisor</li>
    <li>ContentSupervisor</li>
    <li>UserSupervisor</li>
    <li>Public</li>
</ul>

<h3>Constraints</h3>
<ul>
    <li>The <code>Account Supervisor</code> should be the highest in hierarchy.</li>
    <li>The <code>Security Supervisor</code> should be below <code>Account Supervisor</code> but higher in hierarchy than <code>User Supervisor</code>.</li>
    <li>The <code>System Supervisor</code> should be sibling to <code>Security Supervisor</code>.</li>
    <li>The <code>User Supervisor</code> should be below <code>Security Supervisor</code> but higher in hierarchy than <code>Public</code>.</li>
</ul>

<h3>Features And Privileges</h3>
TBA