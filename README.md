# Export Attachments from ArcGIS Pro

This guide provides step-by-step instructions for exporting attachments from a feature class in ArcGIS Pro using a File Geodatabase.

## Prerequisites

- ArcGIS Pro software installed
- Access to a File Geodatabase with feature class attachments

## Steps

### 1. Export File Geodatabase

Export your data as a "File Geodatabase" format from ArcGIS Online.

1. Navigate to the **Data** tab in your ArcGIS Online layer
2. Click on **Export**
3. Select **File Geodatabase** from the dropdown menu

![Export File Geodatabase](./images/step1-export-geodatabase.png)
*Figure 1: Selecting File Geodatabase export option*

### 2. Add Folder Connection in ArcGIS Pro

1. Open ArcGIS Pro
2. In the Catalog pane, right-click on **Folders**
3. Select **Add Folder Connection** (or press Ctrl+Shift+C)
4. Browse to and select your Geodatabase location
5. Confirm the connection

![Add Folder Connection](./images/step2-add-folder-connection.png)
*Figure 2: Adding folder connection in ArcGIS Pro*

### 3. Add the Batch Export Script

Follow the official ESRI documentation to set up the batch export script:

**Resource:** [How To: Batch export attachments from a feature class](https://support.esri.com/en-us/knowledge-base/how-to-batch-export-attachments-from-a-feature-class-in-000017450)

This script enables automated export of multiple attachments from your feature class.

### 4. Export the Attachments

1. Run the batch export script
2. Specify your output directory
3. Execute the export process
4. Verify that attachments have been successfully exported

## Additional Resources

- [ArcGIS Pro Documentation](https://pro.arcgis.com/)
- [ESRI Support](https://support.esri.com/)


---

*Last updated: December 2025*
