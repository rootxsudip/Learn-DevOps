### AWS Guide
* Register
* Go to my console
* Sign-in as root user
* Always sign-in as IAM user because it doesn't have all permissions as root user.(Setup will done below)
 
### Setup Billing and Cost Management
* This section shows all about bill and costs of the aws
* Here we will create a budget
* Option:
  * Use a template (simplified)
  * Monthly cost budget
  * Budget Cost: $10
  * Email Recipients - your email
* Create budget
* It will send you three notification which are about: you used 85% of the budget, budget exceed or soon it will be exceed
**In account settings you can turn on: IAM user/role access to billing information**

### IAM: This is service is called identity access management. It used to configure the permissions of user and group.
#### Create a user
* Setup username
* Provide user access to the AWS Management Console - optional
* I want to create an IAM user
* Attach policies directly - Administrator Access

#### Group: Create group with permissions and it will give access to same type of permissions for all users belong in the group.
* Create group with admin access permission
* Add user

