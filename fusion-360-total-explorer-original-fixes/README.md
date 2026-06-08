# Changes from the original version to this

1. Added functionality to catch an error if trying to export as IGES and the user does not have the required permissions (e.g. holding a 'Not for Commercial Use' licence)

2. Added functionality to start from a particular project index (to help if re-running after an error).  Change the self.project_start variable in line 31 to do this.

3. Added functionality to ignore a particular model - this is specified in the self.components_to_ignore_dxf list in line 34.

This seemed to fix all of my issues when I exported my Fusion 360 models in June 2026.
