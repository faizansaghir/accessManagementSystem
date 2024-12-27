<h1>Overview</h1>

This project is to build an Access Management System which will be similar to Access Management in Snowflake. <br>

<h1>Process</h1>

<h2>Requirements</h2>
<ul>
    <li>There will be some pre-defined roles which will have privileges specific to those roles</li>
    <li>These pre-defined roles will have a hierarchy in place.</li>
    <li>Users can create new account</li>
    <li>For each account we will have its associated roles and users</li>
</ul>

<h3>Roles</h3>
<ul>
    <li>AccountSupervisor</li>
    <li>SecuritySupervisor</li>
    <li>ContentSupervisor</li>
    <li>UserSupervisor</li>
    <li>Public</li>
</ul>

<h4>Constraints</h4>
<ul>
    <li>The <code>Account Supervisor</code> should be the highest in hierarchy.</li>
    <li>The <code>Security Supervisor</code> should be below <code>Account Supervisor</code> but higher in hierarchy than <code>User Supervisor</code>.</li>
    <li>The <code>System Supervisor</code> should be sibling to <code>Security Supervisor</code>.</li>
    <li>The <code>User Supervisor</code> should be below <code>Security Supervisor</code> but higher in hierarchy than <code>Public</code>.</li>
</ul>

<h4>Features And Privileges</h4>
TBA

<h2>Flows</h2>
<h3>Account Creation</h3>
TBA
<h3>Account Login</h3>
TBA
<h3>User login for an Account</h3>
TBA
