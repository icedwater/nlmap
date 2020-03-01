# Ideas

 - need to be able to identify GPS coordinates of locations
 - reverse geocoding tends to have API limits
 - we need to cache them somewhere to reduce network dependency
 - luckily, street names and locations don't often change

## Database Schema

 - **Location Name**: street or building or landmark
 - **Location Type**: see above
 - **Coordinates**:
    - for points of interest, we try to find a reasonable centre
      - do we manually compute these, or is reverse geocoding enough?
    - minimal set is needed to trace a street
 - anything else?
   - alternate name
   - name in other language
