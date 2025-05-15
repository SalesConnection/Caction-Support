## How to Set Up Project Template?

**Project Template** controls the structure and required fields for a project, ensuring consistency and efficiency. It allows you to define what information must be filled in when creating a project.

<br>

**Click on a section below to navigate.**<br>

- [Template Info](#section1)<br>
- [Details Variable Settings](#section2)<br>
- [Project Settings](#section3)<br>
- [Prepopulate Assigned User](#section4)<br>
- [Default Field](#section5)<br>
- [Custom Field](#section6)
  <br><br>

# Project Template

1. To access and configure a Project Template, go to desktop's navigation bar:

   - Select **Template Settings**
   - Then select **Project Templates**

   **Open Project Templates Here**: [https://system.caction.com/templateSettings/DealTemplates](https://system.caction.com/templateSettings/DealTemplates)<br>

   _Note: The template configuration will affect both the web and mobile applications. If you do not have access to the Template Settings page, please contact your admin._<br>

    <br>
    <p align="center">
    <img src="img/Project_Template_Step_1.png" alt="Project Template Step 1">
    </p>

    <br>

   <a id="section1"></a>

# Template Info

2. The Template Info section serves as the foundation for your project template configuration.

   The Template Info section contains 5 fields:<br>

   | Term                | Definition                                                                            |
   | ------------------- | ------------------------------------------------------------------------------------- |
   | Project Category    | Specifies the type of project this template is used for.                              |
   | Template Short Code | A brief identifier to easily reference the template.                                  |
   | Template Name       | The display name of the template, customizable to match its purpose.                  |
   | Outstanding Label   | Defines a label for pending actions, tasks, or amounts related to the project.        |
   | Collection Label    | Sets a label for grouped elements, such as collected payments or categorized records. |

   <br>
   <p align="center">
   <img src="img/Project_Template_Step_2.png" alt="Project Template Step 2">
   </p>

   <br>

   In the Template Info section, you can customize several important labels. The Template Info section serves as the foundation for your project template configuration. You can customize customize key labels to fit your needs.

   After saving your changes, the system will apply your custom labels throughout the interface.

<br>
<a id="section2"></a>

# Details Variable Settings

3. The Details Variable Settings section allows you to customize the information displayed across the system wherever card views are used, such as the Project Dashboard.

   When you open the settings, you can drag variable elements to the left box to customize your view.

    <br>
    <p align="center">
    <img src="img/Project_Template_Step_6.png" alt="Project Template Step 6">
    </p>

When you open the settings, you can drag a field to the left box to customize your view.

- **Step 1:** Click the "⚙️ Open Settings" icon (highlighted in red below) to open the field options.

- **Step 2:** In the popup window, you'll see available variables on the right side.

  For Example, Dragging 'Amount' to replace 'Project End Date' in the Details Variable Settings will update the project dashboard to display 'Amount' on project cards instead.

- **Step 3**: After saving, your project dashboard will display the "amount" information in the project cards instead of the "Project End Date".

<br>
<a id="section3"></a>

# Project Settings

4. Project Settings in the Project Template control section visibility and configure Product/Service settings for projects. This ensures that only relevant sections are displayed and that product/service options align with project requirements.

   <br>
   <p align="center">
   <img src="img/Project_Template_Step_8.png" alt="Project Template Step 8">
   </p>

   <br>

### Project Category

- When this toggle is off, the categories section will be hidden when viewing project details or adding a new project.

### Product/Services View Settings

   <br>
   <p align="center">
       <img src="img/Project_Template_Step_9.png" alt="Project Template Step 9">
   </p>

   <br>

The Enable section visibility provides settings for three different user roles, giving you precise control over your project management interface for different user types.

   <br>
   <p align="center">
       <img src="img/Project_Template_Step_10.png" alt="Project Template Step 10">
   </p>

   <br>

Each visibility setting can be independently configured with a dropdown menu with options:

- Default Settings - Shows everything as normal
- Hide Amount Field - Hides only the financial information (Green section)
- Hide Whole Section - Hides the entire Product/Services section (Red section)

### Collection View Settings

   <br>
   <p align="center">
       <img src="img/Project_Template_Step_11.png" alt="Project Template Step 11">
   </p>

   <br>

It enables collection amount visibility for respective user types, allowing access for different user roles:

- Admin Visibility
- Subadmin Visibility
- Staff Visibility

   <br>
   <p align="center">
       <img src="img/Project_Template_Step_12.png" alt="Project Template Step 12">
   </p>

_Note: This is the Project Details - Collection section._

   <br>

### Project End Date View Settings

   <br>
   <p align="center">
       <img src="img/Project_Template_Step_13.png" alt="Project Template Step 13">
   </p>

   <br>

Similar to Collection view, it enables project end date visibility for respective user types:

- Admin Visibility
- Subadmin Visibility
- Staff Visibility

   <br>

### Product/Services Settings

   <br>
   <p align="center">
       <img src="img/Project_Template_Step_14.png" alt="Project Template Step 14">
   </p>

   <br>

Force Project Product/Services Selection is a setting that determines whether the Product/Services section is required when creating a new project.

This ensures that all projects have associated products or services.

   <br>
   <a id="section4"></a>

# Prepopulate Assigned User

5.  Prepopulate Assigned User automatically assigns the user to the customer during Project Creation.

    <br>
       <p align="center">
    <img src="img/Project_Template_Step_15.png" alt="Project Template Step 15">
    </p>

    <br>

    <a id="section5"></a>

# Default Field

6.  **Default Field Pre-Populate Value Settings**

    This section manages default fields, which are system-defined and cannot be customized. These fields appear across all project categories and remain fixed,

    These fields serve as the default information for a project, ensuring essential details are always available. except for the Integration Code, which activates only when system integration is required. Additionally, auto-populate values can be set if needed, allowing predefined inputs to streamline data entry.

    <br>

    <p align="center">
    <img src="img/Project_Template_Step_16.png" alt="Project Template Step 16">
    </p>

    <br>

    <a id="section6"></a>

# Custom Field

7. A custom field is a user-defined field that you can add to your project template beyond the standard default fields.

   <br>
   <p align="center">
       <img src="img/Project_Template_Step_17.png" alt="Project Template Step 17">
   </p>

   <br>

   ### Custom Field Element (left panel):

   This shows the available field types that can be added to the template.

   |       Term        | Definition                                                        |
   | :---------------: | :---------------------------------------------------------------- |
   |       Text        | Simple single-line text fields for basic information              |
   |     Text Area     | Larger multi-line text fields for longer notes                    |
   |      Number       | Fields that accept only numerical values                          |
   |       Date        | Calendar-based fields for selecting dates                         |
   |     Date Time     | Fields that capture both date and time information                |
   |     Drop Down     | Selection fields with predefined options in a dropdown menu       |
   | Multiple Checkbox | Fields that allow selecting multiple options from a list          |
   |    Attachment     | Fields that allow users to upload and attach files to the project |

    <br>

   ### Custom Field View (right panel):

    <br>
    <p align="center">
    <img src="img/Project_Template_Step_18.png" alt="Project Template Step 18">
    </p>

    <br>

   The Custom Field View panel shows the actual custom fields that have been configured for this Project Template.

   For each field you can decide:

   ### Editable Field

   - Controls access to modify the field's content (Only Admin has the access to edit even after closing the field)

   ### Required Field

   - Makes the field mandatory before saving

   ### Locked Field

   - Locks the field, preventing any modifications even by users who would normally have edit permissions

   ### Access Permission

   - Controls which users can see the field during project creation

   ### Pre-populate Value

   - Sets default values that appear automatically in the field

    <br>

   ## Settings Section

   8. This dropdown menu shows three management options:

      <br>
      <p align="center">
      <img src="img/Project_Template_Step_19.png" alt="Project Template Step 19">
      </p>
      <br>

   ### Version history

   - Access to previous versions of the template , Restore previous versions by clicking the "Restore" button in the bottom-right.

      <br>
      <p align="center">
      <img src="img/Project_Template_Step_20.png" alt="Project Template Step 18">
      </p>

       <br>

   ### Save to all categories

   - Use this function when you want the same template configuration to apply to multiple or all project categories in your system (Enter notes about your changes)

      <br>
      <p align="center">
      <img src="img/Project_Template_Step_21.png" alt="Project Template Step 18">
      </p>

      <br>

   ### Copy from

   - Importation of settings from alternative templates, select the categories you want to copy from and apply it.

      <br>
      <p align="center">
      <img src="img/Project_Template_Step_22.png" alt="Project Template Step 18">
      </p>

       <br>
