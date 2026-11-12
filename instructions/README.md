# Welcome to your lab environment

To begin, log into the virtual machine using the following credentials:

**Virtual machine:** `Win11-Pro-Base`

**Username:** +++AlexW@@lab.CloudCredential(WWLM365EnterprisewithCalling).TenantName+++

**Temporary Access Pass:** +++@lab.Variable(TAP)+++

**User password:** +++@lab.CloudCredential(WWLM365EnterprisewithCalling).UserPassword+++

**Admin username:** +++@lab.CloudCredential(WWLM365EnterprisewithCalling).AdministrativeUsername+++

**Admin Temporary Access Pass:** +++@lab.Variable(TAP2)+++

**Admin password:** +++@lab.CloudCredential(WWLM365EnterprisewithCalling).AdministrativePassword+++

---

## Foundations for Teams administration at scale

### Delegate granular permissions with Teams Custom RBAC

1. Open a browser and navigate to +++https://admin.teams.microsoft.com/+++.
2. Sign in with the admin user credentials.
3. In the left navigation, select **Roles & Admins**.
4. Select **Create new role**. In the wizard, enter the name +++Ignite Teams Selected Policy Role XXXX+++ for this custom role.
5. Enter +++Manage selected Teams policies for the Ignite lab.+++ as the description.
6. Select **Next** to open the Permissions step.
7. Select one or more specific types of policy permissions from the list.
8. Select **Next** to go to Assign Users/Groups. Select **Add Assignments**, search for +++Test user+++, and select a user.
9. Select **Apply** to confirm the selection, then select **Next**.
10. Review the selected permissions and assignments. Select **Save** to create the custom role.

### Monitor your organization's meetings from one place

1. Navigate to **Meetings > Meetings**.
2. Review the list of **In-progress meetings**.
3. Locate +++[specific in-progress meeting]+++ by searching for the organizer name.
4. Select the meeting to open its details. Review the issue summary and participant list.
5. Open an issue to review the affected participants and available diagnostic information.
6. Open **Completed meetings** and set the date range to the last seven days.
7. Review the available audio, video, and screen-sharing telemetry. Select a time window around the issue and compare the telemetry with the reported symptoms.
8. Select a meeting with an issue.
9. Select **Issues** to review details about root causes and recommendations.
10. Clear the filter.
11. Search for +++Meeting code+++.
12. Open the meeting and examine degradation trends, the suggested root cause, and mitigation steps.
13. Review **Insights**.
14. Select details to view the finding, possible root causes, and mitigation recommendations.
15. Select **View user details** to see the list of users affected by the issue.
16. Navigate to **Meetings > Calls**.
17. Review the list of **Completed Calls**.
18. Search by caller or callee name to filter the list.

---

## AI-powered Teams administration

### On-Canvas Search

1. Navigate to **Users > Manage Users**.
2. Search for +++User Query 01+++.
3. Select **Export** to save the filtered list of users.
4. Search for +++User Query 02+++.
5. Search for +++User Query 03+++.

### On-Canvas Policy

1. Navigate to **Users > Manage Users**.
2. Search for +++User Query 01+++.
3. Select **Export** to save the filtered list of users.
4. Search for +++User Query 02+++.
5. Search for +++User Query 03+++.

### Meeting troubleshooting

1. Navigate to **Users > Manage Users**.
2. Search for +++User Query 01+++.
3. Select **Export** to save the filtered list of users.
4. Search for +++User Query 02+++.
5. Search for +++User Query 03+++.

---

## Administering Teams Rooms and Teams devices

### Access the Pro Management Portal

1. Open a new browser tab and navigate to +++https://portal.rooms.microsoft.com/+++.
2. Sign in using the admin credentials provided for this lab.
3. You can also access the Pro Management Portal using the link in the Teams admin center.
4. Review the navigation menu and locate **Rooms**, **Phones**, **Planning**, **Updates**, and **Settings**.

### Set up your room inventory and groups

1. In the left navigation menu, go to **Planning > Inventory**.
2. Select **Get Data** to begin populating the portal with room resource accounts from your Microsoft 365 tenant.
3. Review the available inventory and locate the room resource account designated for this lab.
4. Go to **Settings > Groups**.
5. Review the existing groups. Groups can reflect your organization's structure to simplify role-based access control and alert reporting.
6. Create a group named +++Ignite Rooms [lab identifier]+++.
7. Add +++[Lab room/device]+++ to the group and save your changes.
8. Open the group and verify its membership.

### Keep Teams devices up to date

1. In the left navigation menu, expand **Updates** and select **Ring Configuration**.
2. Review the **Staging**, **General**, and **Executive** rings shown in the lab environment.
3. Compare the number of devices assigned to each ring and the configured completion times.
4. Open the **General** ring and locate +++[Lab room/device]+++.
5. Move the designated device to the **Staging** ring and save the assignment.
6. Open the **Staging** ring and verify that the device is now assigned to it.
7. Review how update rings let you test updates on a small set of devices before deploying them more broadly.
8. Open **Updates > Update Management** and review the update information available for the designated device.

### Investigate device issues

1. Go to **Rooms** or **Phones**, depending on the device assigned for this lab.
2. Select +++[Lab room/device]+++.
3. Open the **Status** tab and review the available health signals.
4. Identify any unhealthy signals and review their details.
5. Open the **Activity** tab and review any recorded remediation activity.
6. Select the **Actions** tab.
7. Review the available troubleshooting actions, including **Log Collection**, **Network Connectivity Test**, and **Restart device-Clear cache**, where available for the selected device.
8. Select **Log Collection**, then select **Run**.
9. Follow the prompts to submit the action.
10. Review the action status and, when complete, access the collected logs using the option provided in the portal.
11. Return to **Status** and review the device's health alongside the diagnostic information collected.

### Review incident integration options — instructor walkthrough

1. Follow the instructor as they review the **ServiceNow integration** or **Incident Webhook** configuration.
2. Review how these integrations can generate IT service management tickets for room issues.
3. If an integration is configured in the lab, review its settings and an example incident or ticket.
