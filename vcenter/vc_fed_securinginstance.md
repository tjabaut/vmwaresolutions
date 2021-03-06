---

copyright:

  years:  2016, 2018

lastupdated: "2018-03-19"

---

# Securing VMware Federal instances

Complete the following procedure to remove the open management connection for ongoing access to your deployed VMware Federal instance.

## Before you begin

Review the following important information to understand the results of securing your deployed VMware Federal instance:

**Important:**

* Record and save any credentials that you may need for your environment before completing this procedure. All credentials for your environment are erased from the {{site.data.keyword.IBM}} database and cannot be retrieved after the secure action is invoked.
* With the exception of a full instance delete, all management functions are disabled after the secure action is invoked.
* The VMware NSX Edge Services Gateway (ESG) for outbound HTTPS management traffic and the IBM CloudDriver virtual machine are deleted as part of the action to secure the deployed VMware Federal instance.

## Procedure

1. Click **Deployed Instances** from the left navigation pane.
2. In the **vCenter Server Instances** table, click the instance to secure.
3. Click the overflow menu icon to the right of **vCenter console**.
4. Click **Secure Instance**.
5. Click **OK** to confirm that you want to disconnect the instance from automation.
   **Note:** Ensure that you have reviewed the important information in **Before you begin** before completing this step.
6. The status of the instance is changed to **Modifying**. When the instance is secured successfully, the status of the instance is changed to **Secured** and only the instance properties and deployment history are available.

## Related links

* [VMware Federal on IBM Cloud overview](vc_fed_overview.html)
* [Ordering VMware Federal instances](vc_fed_orderinginstance.html)
* [Viewing VMware Federal instances](vc_fed_viewinginstance.html)
* [Deleting VMware Federal instances](vc_fed_deletinginstance.html)
* [Contacting IBM Support](../vmonic/trbl_support.html)
