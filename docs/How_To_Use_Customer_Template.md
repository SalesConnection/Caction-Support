# Customer Template

**Customer Template** is a standardized format or structure used in customer relationship management (CRM) systems to consistently collect and organize customer information.

_Note: The template configuration for these functions will affect both the web and mobile app_

## Table of Contents

- [Template Info](#template-info)
- [Details Privacy Settings](#details-privacy-settings)
- [Details Variable Settings](#details-variable-settings)
- [Quick Search Settings](#quick-search-settings)
- [Prepopulate Assigned User](#prepopulate-assigned-user)
- [Default Field](#default-field)
- [Custom Field](#custom-field)

## Getting Started

1. From the desktop's navigation bar:

   - Select **Template Settings**
   - Then select **Customer Templates**

   **Open Project Templates Here**:
   [https://system.caction.com/templateSettings/CustomerTemplates](https://system.caction.com/templateSettings/CustomerTemplates)

   _Note: If you do not have access to the Template Settings page, please contact your administrator._

   <p align="center">
      <img src="img/Customer_Template_Step_1.png" alt="Customer Template Step 1">
   </p>

## Template Info

2. The Template Info section contains 5 fields:

   - Customer Category
   - Template Short code
   - Template Name
   - Company Label
   - Name Label

   <p align="center">
     <img src="img/Customer_Template_Step_2.png" alt="Customer Template Step 2">
   </p>

   ### Customer Category

   The Category field provides a dropdown menu for selecting different customer template categories for editing. The current selection is "Healthcare Facilities".

   <p align="center">
     <img src="img/Customer_Template_Step_3.png" alt="Customer Template Step 3">
   </p>

   ### Template Short code

   The short code represents the customer code identifier (example: the first customer created will be assigned "C0001").

   <p align="center">
     <img src="img/Customer_Template_Step_3_1.png" alt="Customer Template Step 4">
   </p>

   ### Template Name

   Template Name modifies the name of the template throughout the system.

   For instance, modifying the Template Name to "Buyer" will replace all instances of "Customer" with "Buyer" across the entire system.

   <p align="center">
     <img src="img/Customer_Template_Step_3_2.png" alt="Customer Template Step 5">
   </p>

   ### Company Label

   This field allows modification of the label name for the company field. It is recommended to prioritize key information in this field, as it is utilized for duplicate checking.

   <p align="center">
     <img src="img/Customer_Template_Step_3_5.png" alt="Customer Template Step 6">
   </p>

   ### Name Label

   This option enables modification of the customer name label.

   <p align="center">
     <img src="img/Customer_Template_Step_3_4.png" alt="Customer Template Step 7">
   </p>

## Details Privacy Settings

3. This section controls the visibility parameters of customer status and customer category in the customer section.

   <p align="center">
     <img src="img/Customer_Template_Step_4.png" alt="Customer Template Step 8">
   </p>

## Details Variable Settings

4. Details Variable Settings provides customization options for displayed customer information fields.

   The section currently displays 5 enabled fields:

   - Customer Name
   - Company Name
   - Status Name
   - Category Name
   - Inquiry Date

   Each field includes a removal option ("X" button).

   The "Open Setting" button provides access to additional field options and configuration modifications.

   <p align="center">
     <img src="img/Customer_Template_Step_6.png" alt="Customer Template Step 10">
   </p>

   The selected fields will be displayed and tracked in the mobile customer list interface.

   <p align="center">
     <img src="img/Customer_Template_Step_6_1.jpg" alt="Customer Template Template 11" style="width: 30%; height: auto;">
   </p>

## Quick Search Settings

5. Quick Search Settings facilitates efficient keyword searches within the customer page.

   <p align="center">
     <img src="img/Customer_Template_Step_7.png" alt="Customer Template Step 12">
   </p>

   When elements such as "customer name" are added to the quick search functionality, users may search by name identifiers to locate specific customer records.

   <p align="center">
     <img src="img/Customer_Template_Step_8.png" alt="Customer Template Step 13">
   </p>

   Selecting "Open Settings" provides options for defining which elements to include in the quick search functionality.

   <p align="center">
     <img src="img/Customer_Template_Step_9.png" alt="Customer Template Step 14">
   </p>

## Prepopulate Assigned User

6. The Prepopulate Assigned User feature enables automatic user assignment during the Customer Creation process.

   <p align="center">
     <img src="img/Customer_Template_Step_10.png" alt="Customer Template Step 15">
   </p>

## Default Field

7. This section displays system default fields that cannot be edited or deleted.

   <p align="center">
     <img src="img/Customer_Template_Step_11.png" alt="Customer Template Step 16">
   </p>

   For each field, the following parameters are configurable:

   ### Editable Field

   - Controls access permissions for field content modification (Only Administrators have access to edit content even when the field is locked)

   ### Required Field

   - Designates the field as mandatory prior to saving records

   ### Access Permission

   - Determines field visibility during customer creation processes

   Upon completing template settings configuration, select the "Save" button to apply and store all changes.

## Custom Field

8. Custom fields are user-defined fields that may be added to customer templates to supplement standard default fields.

   <p align="center">
     <img src="img/Customer_Template_Step_12.png" alt="Customer Template Step 17">
   </p>

   ### Custom Field Element (Left panel):

   This displays available field types that may be added to the template:

   |    Field Type     | Definition                                                     |
   | :---------------: | :------------------------------------------------------------- |
   |       Text        | Simple single-line text fields for basic information           |
   |     Text Area     | Larger multi-line text fields for extended notes               |
   |      Number       | Fields that accept only numerical values                       |
   |       Date        | Calendar-based fields for date selection                       |
   |     Date Time     | Fields that capture both date and time information             |
   |     Drop Down     | Selection fields with predefined options in a dropdown menu    |
   | Multiple Checkbox | Fields that enable selection of multiple options from a list   |
   |    Attachment     | Fields that enable file uploads and attachments to the project |

   ### Custom Field View (Right panel):

   For each custom field, the following parameters are configurable:

   ### Locked Field

   - Prevents any modifications to the field, including by users who would typically have edit permissions.

   ### Enabled Field

   - When enabled (toggled on), the field will be displayed and available for implementation on customer forms.

   Upon completing custom field configuration, select the "Save" button to apply and store all changes.

<br>

## Settings section

9. This dropdown menu provides additional management options:

   <p align="center">
     <img src="img/Customer_Template_Step_14.png" alt="Customer Template Step 19">
   </p>

   |       Field Type       | Definition                                                                                                            |
   | :--------------------: | :-------------------------------------------------------------------------------------------------------------------- |
   |    Version history     | Access to previous versions of the template                                                                           |
   | Save to all categories | Implementation of changes across all customer categories                                                              |
   |       Copy from        | Importation of settings from alternative templates                                                                    |
   |          Save          | It is essential to save all work after implementing changes to template settings to ensure configuration preservation |
