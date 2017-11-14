<html>
 <body>
  <h1>MAVLink Include Files</h1>
  <p>
   <strong>
    <em>Including files:</em>common.xml</strong>
  </p>
  <h1>MAVLink Type Enumerations</h1>
  <h2 class="mavlink_message_name" id="UALBERTA_AUTOPILOT_MODE" name="ENUM_UALBERTA_AUTOPILOT_MODE">UALBERTA_AUTOPILOT_MODE</h2>
  <p class="description">Available autopilot modes for ualberta uav</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">CMD ID</th>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field" id="MODE_MANUAL_DIRECT">
     <td class="mavlink_type" valign="top">
     </td>
     <td class="mavlink_name" valign="top">MODE_MANUAL_DIRECT</td>
     <td class="mavlink_comment">Raw input pulse widts sent to output</td>
    </tr>
    <tr class="mavlink_field" id="MODE_MANUAL_SCALED">
     <td class="mavlink_type" valign="top">
     </td>
     <td class="mavlink_name" valign="top">MODE_MANUAL_SCALED</td>
     <td class="mavlink_comment">Inputs are normalized using calibration, the converted back to raw pulse widths for output</td>
    </tr>
    <tr class="mavlink_field" id="MODE_AUTO_PID_ATT">
     <td class="mavlink_type" valign="top">
     </td>
     <td class="mavlink_name" valign="top">MODE_AUTO_PID_ATT</td>
     <td class="mavlink_comment">dfsdfs</td>
    </tr>
    <tr class="mavlink_field" id="MODE_AUTO_PID_VEL">
     <td class="mavlink_type" valign="top">
     </td>
     <td class="mavlink_name" valign="top">MODE_AUTO_PID_VEL</td>
     <td class="mavlink_comment">dfsfds</td>
    </tr>
    <tr class="mavlink_field" id="MODE_AUTO_PID_POS">
     <td class="mavlink_type" valign="top">
     </td>
     <td class="mavlink_name" valign="top">MODE_AUTO_PID_POS</td>
     <td class="mavlink_comment">dfsdfsdfs</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="UALBERTA_NAV_MODE" name="ENUM_UALBERTA_NAV_MODE">UALBERTA_NAV_MODE</h2>
  <p class="description">Navigation filter mode</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">CMD ID</th>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field" id="NAV_AHRS_INIT">
     <td class="mavlink_type" valign="top">
     </td>
     <td class="mavlink_name" valign="top">NAV_AHRS_INIT</td>
     <td class="mavlink_comment">
     </td>
    </tr>
    <tr class="mavlink_field" id="NAV_AHRS">
     <td class="mavlink_type" valign="top">
     </td>
     <td class="mavlink_name" valign="top">NAV_AHRS</td>
     <td class="mavlink_comment">AHRS mode</td>
    </tr>
    <tr class="mavlink_field" id="NAV_INS_GPS_INIT">
     <td class="mavlink_type" valign="top">
     </td>
     <td class="mavlink_name" valign="top">NAV_INS_GPS_INIT</td>
     <td class="mavlink_comment">INS/GPS initialization mode</td>
    </tr>
    <tr class="mavlink_field" id="NAV_INS_GPS">
     <td class="mavlink_type" valign="top">
     </td>
     <td class="mavlink_name" valign="top">NAV_INS_GPS</td>
     <td class="mavlink_comment">INS/GPS mode</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="UALBERTA_PILOT_MODE" name="ENUM_UALBERTA_PILOT_MODE">UALBERTA_PILOT_MODE</h2>
  <p class="description">Mode currently commanded by pilot</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">CMD ID</th>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field" id="PILOT_MANUAL">
     <td class="mavlink_type" valign="top">
     </td>
     <td class="mavlink_name" valign="top">PILOT_MANUAL</td>
     <td class="mavlink_comment">sdf</td>
    </tr>
    <tr class="mavlink_field" id="PILOT_AUTO">
     <td class="mavlink_type" valign="top">
     </td>
     <td class="mavlink_name" valign="top">PILOT_AUTO</td>
     <td class="mavlink_comment">dfs</td>
    </tr>
    <tr class="mavlink_field" id="PILOT_ROTO">
     <td class="mavlink_type" valign="top">
     </td>
     <td class="mavlink_name" valign="top">PILOT_ROTO</td>
     <td class="mavlink_comment">Rotomotion mode</td>
    </tr>
   </tbody>
  </table>
  <h1>MAVLink Messages</h1>
  <h2 class="mavlink_message_name" id="NAV_FILTER_BIAS" name="NAV_FILTER_BIAS">NAV_FILTER_BIAS (<a href="
      #NAV_FILTER_BIAS">
    #220
   </a>
   )
  </h2>
  <p class="description">Accelerometer and Gyro biases from the navigation filter</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">usec</td>
     <td class="mavlink_type" valign="top">uint64_t</td>
     <td class="mavlink_comment">Timestamp (microseconds)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">accel_0</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">b_f[0]</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">accel_1</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">b_f[1]</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">accel_2</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">b_f[2]</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">gyro_0</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">b_f[0]</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">gyro_1</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">b_f[1]</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">gyro_2</td>
     <td class="mavlink_type" valign="top">float</td>
     <td class="mavlink_comment">b_f[2]</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="RADIO_CALIBRATION" name="RADIO_CALIBRATION">RADIO_CALIBRATION (<a href="
      #RADIO_CALIBRATION">
    #221
   </a>
   )
  </h2>
  <p class="description">Complete set of calibration parameters for the radio</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">aileron</td>
     <td class="mavlink_type" valign="top">uint16_t[3]</td>
     <td class="mavlink_comment">Aileron setpoints: left, center, right</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">elevator</td>
     <td class="mavlink_type" valign="top">uint16_t[3]</td>
     <td class="mavlink_comment">Elevator setpoints: nose down, center, nose up</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">rudder</td>
     <td class="mavlink_type" valign="top">uint16_t[3]</td>
     <td class="mavlink_comment">Rudder setpoints: nose left, center, nose right</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">gyro</td>
     <td class="mavlink_type" valign="top">uint16_t[2]</td>
     <td class="mavlink_comment">Tail gyro mode/gain setpoints: heading hold, rate mode</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">pitch</td>
     <td class="mavlink_type" valign="top">uint16_t[5]</td>
     <td class="mavlink_comment">Pitch curve setpoints (every 25%)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">throttle</td>
     <td class="mavlink_type" valign="top">uint16_t[5]</td>
     <td class="mavlink_comment">Throttle curve setpoints (every 25%)</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="UALBERTA_SYS_STATUS" name="UALBERTA_SYS_STATUS">UALBERTA_SYS_STATUS (<a href="
      #UALBERTA_SYS_STATUS">
    #222
   </a>
   )
  </h2>
  <p class="description">System status specific to ualberta uav</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Type</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">mode</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">System mode, see UALBERTA_AUTOPILOT_MODE ENUM</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">nav_mode</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Navigation mode, see UALBERTA_NAV_MODE ENUM</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">pilot</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Pilot mode, see UALBERTA_PILOT_MODE</td>
    </tr>
   </tbody>
  </table>
 </body>
</html>