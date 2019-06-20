# FME_Workspace_Examples
A collection of useful FME workspace examples which can be used for demonstration purposes.

## XYZPointCloudThinner
This workspace demonstates how to read a point cloud in XYZ format, thin it by sampling using the PointCloudThinner transformer to extract every tenth point, and write out the resulting XYZ file with revised column names in the header row.

**NOTE:** This flow assumes that the input and output files contain seven components XYZRGBI where with the seventh column contains the return intensity or some other scalar value.
