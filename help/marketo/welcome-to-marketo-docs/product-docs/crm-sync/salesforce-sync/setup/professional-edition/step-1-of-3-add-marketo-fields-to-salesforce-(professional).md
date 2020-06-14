---
unique-page-id: 11372975
description: Step 1 of 3: Add Marketo Fields to Salesforce  (Professional) - Marketo Docs - Product Documentation
title: Step 1 of 3: Add Marketo Fields to Salesforce  (Professional)
---

# Step 1 of 3: Add Marketo Fields to Salesforce (Professional) {#step-of-add-marketo-fields-to-salesforce-professional}

Step 1 of 3: Add Marketo Fields to Salesforce (Professional) - Marketo Docs - Product Documentation

>[!NOTE]
>
>**Prerequisites**
>
>Your Salesforce instance must have access to Salesforce API's to sync data between Marketo and Salesforce.

`Marketo uses a set of fields to capture certain kinds of marketing related information. If you would like this data in Salesforce, please follow the instructions below.`

1. `Create three custom fields in Salesforce on the lead and contact objects: Score, Acquisition Program, and Acquisition Date.`
1. Map these custom fields between leads and contacts so that on conversion in Salesforce, the values carry over.
1. You can create other additional fields, if necessary (see the table below).

All of these custom fields are optional and are not required to sync Marketo and Salesforce. As a best practice, we recommend that you do create fields for Score, `Acquisition Program, and Acquisition Date.`

### What's in this article? {#what-s-in-this-article}

[Add Marketo Fields to Salesforce](#step1of3-addmarketofieldstosalesforce(professional)-addmarketofieldstosalesforce)  
[Map Custom Fields for Conversions](#step1of3-addmarketofieldstosalesforce(professional)-mapcustomfieldsforconversions)

#### Add Marketo Fields to Salesforce {#step1of3-addmarketofieldstosalesforce(professional)-addmarketofieldstosalesforce}

Add three custom fields on the lead and contact objects in Salesforce listed above. If you want to add more, see the table of available fields at the end of this section.

Perform the following steps for each of the three custom fields to add them. Start with **Score**.

##### 1. Log into Salesforce and click Setup. {#step1of3-addmarketofieldstosalesforce(professional)-logintosalesforceandclicksetup.}

** ![](assets/image2016-5-23-13-3a15-3a21.png)

**

##### 2. In the Build menu on the left, click Customize and select Leads. Click Fields. {#step1of3-addmarketofieldstosalesforce(professional)-inthebuildmenuontheleft-clickcustomizeandselectleads.clickfields.}

![](assets/image2016-5-23-13-3a20-3a5.png)

##### 3. Click New in the Custom Fields & Relationships section at the bottom of the page. {#step1of3-addmarketofieldstosalesforce(professional)-clicknewinthecustomfields&relationshipssectionatthebottomofthepage.}

![](assets/image2016-5-26-14-3a41-3a40.png)

##### 4. Choose the appropriate field type (for Score — number; Acquisition Program — text; Acquisition Date — Date/Time). {#step1of3-addmarketofieldstosalesforce(professional)-choosetheappropriatefieldtype(forscore—number-acquisitionprogram—text-acquisitiondate—date/time).}

![](assets/choose-field-type-2-hand.png)

##### 5. Click Next. {#step1of3-addmarketofieldstosalesforce(professional)-clicknext.}

![](assets/image2016-5-26-14-3a51-3a14.png)

##### 6. Enter the Field Label, Length, and Field Name for the field, as shown in the table below.  {#step1of3-addmarketofieldstosalesforce(professional)-enterthefieldlabel-length-andfieldnameforthefield-asshowninthetablebelow.}

<table class="confluenceTable"> 
 <thead> 
  <tr> 
   <th> 
    <div class="tablesorter-header-inner">
      Field Label 
    </div></th> 
   <th> 
    <div class="tablesorter-header-inner">
      Field Name 
    </div></th> 
   <th> 
    <div class="tablesorter-header-inner">
      Data Type 
    </div></th> 
   <th> 
    <div class="tablesorter-header-inner">
      Field Attributes 
    </div></th> 
  </tr> 
 </thead> 
 <tbody> 
  <tr> 
   <td>Score</td> 
   <td>mkto71_Lead_Score</td> 
   <td>Number</td> 
   <td>Length 10<br>Decimal Places 0 </td> 
  </tr> 
  <tr> 
   <td>Acquisition Date</td> 
   <td>mkto71_Acquisition_Date</td> 
   <td>Date/Time</td> 
   <td> </td> 
  </tr> 
  <tr> 
   <td>Acquisition Program</td> 
   <td>mkto71_Acquisition_Program</td> 
   <td>Text</td> 
   <td>Length 255</td> 
  </tr> 
 </tbody> 
</table>

>[!NOTE]
>
>Salesforce appends __c to Field Names when it uses them to create API Names.

`  
`   ![](assets/image2016-5-26-14-3a55-3a33.png)

>[!NOTE]
>
>Text and number fields require a length, but Date/Time fields don't. A description is optional.

##### 7. Click Next. {#step1of3-addmarketofieldstosalesforce(professional)-clicknext..1}

![](assets/image2016-5-23-14-3a50-3a5.png)

##### 8. Specify the access settings and click Next: {#step1of3-addmarketofieldstosalesforce(professional)-specifytheaccesssettingsandclicknext-}

* Set all roles to **Visible **and **Read-Only**

* Clear the **Read-Only** checkbox for the profile of your sync user:

    * If you have a user with the profile of a *System Administrator* as the sync user, clear the **Read-Only** checkbox for the System Administrator profile (as shown below)
    
    * If you created a *custom profile* for the sync user, clear the **Read-Only** checkbox for that custom profile

![](assets/image2016-6-30-9-3a25-3a4.png)

##### 9. Choose the page layouts that should display the field. {#step1of3-addmarketofieldstosalesforce(professional)-choosethepagelayoutsthatshoulddisplaythefield.}

![](assets/image2016-5-26-15-3a14-3a45.png)

##### 10. Click Save & New to go back and create each of the other two custom fields. Click Save with you're done with all three.  {#step1of3-addmarketofieldstosalesforce(professional)-clicksave&newtogobackandcreateeachoftheothertwocustomfields.clicksavewithyou'redonewithallthree.}

![](assets/image2016-5-23-15-3a8-3a43.png)

##### 11. In the Build menu on the left, click Customize and select Contacts. Click Fields. {#step1of3-addmarketofieldstosalesforce(professional)-inthebuildmenuontheleft-clickcustomizeandselectcontacts.clickfields.}

##### 12. Perform steps 3 through 10 for the Score, Acquisition Date, and Acquisition Program fields on the contact object, just as you did for the lead object. {#step1of3-addmarketofieldstosalesforce(professional)-performsteps3through10forthescore-acquisitiondate-andacquisitionprogramfieldsonthecontactobject-justasyoudidfortheleadobject.}

##### 13. Optionally, use the above procedure for any additional custom fields from this table. {#step1of3-addmarketofieldstosalesforce(professional)-optionally-usetheaboveprocedureforanyadditionalcustomfieldsfromthistable.}

<table class="confluenceTable"> 
 <tbody> 
  <tr> 
   <th>Field Label</th> 
   <th>Field Name</th> 
   <th>Data Type</th> 
   <th>Field Attributes</th> 
  </tr> 
  <tr> 
   <td>Acquisition Program Id</td> 
   <td>mkto71_Acquisition_Program_Id</td> 
   <td>Number</td> 
   <td>Length 18<br>Decimal Places 0 </td> 
  </tr> 
  <tr> 
   <td>Original Referrer</td> 
   <td>mkto71_Original_Referrer</td> 
   <td>Text</td> 
   <td>Length 255</td> 
  </tr> 
  <tr> 
   <td>Original Search Engine</td> 
   <td>mkto71_Original_Search_Engine</td> 
   <td>Text</td> 
   <td>Length 255</td> 
  </tr> 
  <tr> 
   <td>Original Search Phrase</td> 
   <td>mkto71_Original_Search_Phrase</td> 
   <td>Text</td> 
   <td>Length 255</td> 
  </tr> 
  <tr> 
   <td>Original Source Info</td> 
   <td>mkto71_Original_Source_Info</td> 
   <td>Text</td> 
   <td>Length 255</td> 
  </tr> 
  <tr> 
   <td>Original Source Type</td> 
   <td>mkto71_Original_Source_Type</td> 
   <td>Text</td> 
   <td>Length 255</td> 
  </tr> 
  <tr> 
   <td>Inferred City</td> 
   <td>mkto71_Inferred_City</td> 
   <td>Text</td> 
   <td>Length 255</td> 
  </tr> 
  <tr> 
   <td>Inferred Company</td> 
   <td>mkto71_Inferred_Company</td> 
   <td>Text</td> 
   <td>Length 255</td> 
  </tr> 
  <tr> 
   <td>Inferred Country</td> 
   <td>mkto71_Inferred_Country</td> 
   <td>Text</td> 
   <td>Length 255</td> 
  </tr> 
  <tr> 
   <td>Inferred Metropolitan Area</td> 
   <td>mkto71_Inferred_Metropolitan_Area</td> 
   <td>Text</td> 
   <td>Length 255</td> 
  </tr> 
  <tr> 
   <td>Inferred Phone Area Code</td> 
   <td>mkto71_Inferred_Phone_Area_Code</td> 
   <td>Text</td> 
   <td>Length 255</td> 
  </tr> 
  <tr> 
   <td>Inferred Postal Code</td> 
   <td>mkto71_Inferred_Postal_Code</td> 
   <td>Text</td> 
   <td>Length 255</td> 
  </tr> 
  <tr> 
   <td>Inferred State Region</td> 
   <td>mkto71_Inferred_State_Region</td> 
   <td>Text</td> 
   <td>Length 255</td> 
  </tr> 
 </tbody> 
</table>

#### Map Custom Fields for Conversions  {#step1of3-addmarketofieldstosalesforce(professional)-mapcustomfieldsforconversions}

A custom field on the lead object in Salesforce should be mapped to a contact field on the contact object so that data is carried over when a conversion occurs.

##### 1. In the top right corner, click Setup. {#step1of3-addmarketofieldstosalesforce(professional)-1.inthetoprightcorner-clicksetup.}

![](assets/image2016-5-26-16-3a34-3a0.png)

##### 2. Type "fields" into the Nav Search without pressing enter. Fields appears under different objects; Click Fields under Leads. {#step1of3-addmarketofieldstosalesforce(professional)-2.type"fields"intothenavsearchwithoutpressingenter.fieldsappearsunderdifferentobjects-clickfieldsunderleads.}

![](assets/image2016-5-26-16-3a36-3a32.png)

##### 3. Go to the Lead Custom Fields & Relationships section and click Map Lead Fields. {#step1of3-addmarketofieldstosalesforce(professional)-3.gototheleadcustomfields&relationshipssectionandclickmapleadfields.}

![](assets/image2016-5-26-16-3a39-3a29.png)

##### 4. Click the drop-down next to the field you want to map. {#step1of3-addmarketofieldstosalesforce(professional)-4.clickthedrop-downnexttothefieldyouwanttomap.}

![](assets/image2016-5-26-16-3a49-3a53.png)

##### 5. Select the corresponding contact custom field. {#step1of3-addmarketofieldstosalesforce(professional)-5.selectthecorrespondingcontactcustomfield.}

![](assets/image2016-5-26-16-3a56-3a23.png)

##### 6. Repeat the above steps for any other fields you've created.  {#step1of3-addmarketofieldstosalesforce(professional)-6.repeattheabovestepsforanyotherfieldsyou'vecreated.}

##### 7. Click Save when you're done. {#step1of3-addmarketofieldstosalesforce(professional)-7.clicksavewhenyou'redone.}

Easy enough, right?

>[!NOTE]
>
>**Deep Dive**
>
>Here's a [video of the entire process](https://nation.marketo.com/videos/1475) that should make it crystal clear!

>[!NOTE]
>
>**Related Articles**
>
>* [Step 2 of 3: Create a Salesforce User for Marketo (Professional)](step-2-of-3-create-a-salesforce-user-for-marketo-(professional).md)
>
