<html>
 <body>
  <h1>MAVLink Protocol Version</h1>
  <p>This file has protocol version: 2. The version numbers range from 1-255.</p>
  <h1>MAVLink Type Enumerations</h1>
  <h2 class="mavlink_message_name" id="MAV_AUTOPILOT" name="ENUM_MAV_AUTOPILOT">MAV_AUTOPILOT</h2>
  <p class="description">Micro air vehicle / autopilot classes. This identifies the individual model.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">CMD ID</th>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field" id="MAV_AUTOPILOT_GENERIC">
     <td class="mavlink_type" valign="top">0</td>
     <td class="mavlink_name" valign="top">MAV_AUTOPILOT_GENERIC</td>
     <td class="mavlink_comment">Generic autopilot, full support for everything</td>
    </tr>
    <tr class="mavlink_field" id="MAV_AUTOPILOT_PIXHAWK">
     <td class="mavlink_type" valign="top">1</td>
     <td class="mavlink_name" valign="top">MAV_AUTOPILOT_PIXHAWK</td>
     <td class="mavlink_comment">PIXHAWK autopilot, http://pixhawk.ethz.ch</td>
    </tr>
    <tr class="mavlink_field" id="MAV_AUTOPILOT_SLUGS">
     <td class="mavlink_type" valign="top">2</td>
     <td class="mavlink_name" valign="top">MAV_AUTOPILOT_SLUGS</td>
     <td class="mavlink_comment">SLUGS autopilot, http://slugsuav.soe.ucsc.edu</td>
    </tr>
    <tr class="mavlink_field" id="MAV_AUTOPILOT_ARDUPILOTMEGA">
     <td class="mavlink_type" valign="top">3</td>
     <td class="mavlink_name" valign="top">MAV_AUTOPILOT_ARDUPILOTMEGA</td>
     <td class="mavlink_comment">ArduPilotMega / ArduCopter, http://diydrones.com</td>
    </tr>
    <tr class="mavlink_field" id="MAV_AUTOPILOT_OPENPILOT">
     <td class="mavlink_type" valign="top">4</td>
     <td class="mavlink_name" valign="top">MAV_AUTOPILOT_OPENPILOT</td>
     <td class="mavlink_comment">OpenPilot, http://openpilot.org</td>
    </tr>
    <tr class="mavlink_field" id="MAV_AUTOPILOT_GENERIC_WAYPOINTS_ONLY">
     <td class="mavlink_type" valign="top">5</td>
     <td class="mavlink_name" valign="top">MAV_AUTOPILOT_GENERIC_WAYPOINTS_ONLY</td>
     <td class="mavlink_comment">Generic autopilot only supporting simple waypoints</td>
    </tr>
    <tr class="mavlink_field" id="MAV_AUTOPILOT_GENERIC_WAYPOINTS_AND_SIMPLE_NAVIGATION_ONLY">
     <td class="mavlink_type" valign="top">6</td>
     <td class="mavlink_name" valign="top">MAV_AUTOPILOT_GENERIC_WAYPOINTS_AND_SIMPLE_NAVIGATION_ONLY</td>
     <td class="mavlink_comment">Generic autopilot supporting waypoints and other simple navigation commands</td>
    </tr>
    <tr class="mavlink_field" id="MAV_AUTOPILOT_GENERIC_MISSION_FULL">
     <td class="mavlink_type" valign="top">7</td>
     <td class="mavlink_name" valign="top">MAV_AUTOPILOT_GENERIC_MISSION_FULL</td>
     <td class="mavlink_comment">Generic autopilot supporting the full mission command set</td>
    </tr>
    <tr class="mavlink_field" id="MAV_AUTOPILOT_INVALID">
     <td class="mavlink_type" valign="top">8</td>
     <td class="mavlink_name" valign="top">MAV_AUTOPILOT_INVALID</td>
     <td class="mavlink_comment">No valid autopilot, e.g. a GCS or other MAVLink component</td>
    </tr>
    <tr class="mavlink_field" id="MAV_AUTOPILOT_PPZ">
     <td class="mavlink_type" valign="top">9</td>
     <td class="mavlink_name" valign="top">MAV_AUTOPILOT_PPZ</td>
     <td class="mavlink_comment">PPZ UAV - http://nongnu.org/paparazzi</td>
    </tr>
    <tr class="mavlink_field" id="MAV_AUTOPILOT_UDB">
     <td class="mavlink_type" valign="top">10</td>
     <td class="mavlink_name" valign="top">MAV_AUTOPILOT_UDB</td>
     <td class="mavlink_comment">UAV Dev Board</td>
    </tr>
    <tr class="mavlink_field" id="MAV_AUTOPILOT_FP">
     <td class="mavlink_type" valign="top">11</td>
     <td class="mavlink_name" valign="top">MAV_AUTOPILOT_FP</td>
     <td class="mavlink_comment">FlexiPilot</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="MAV_TYPE" name="ENUM_MAV_TYPE">MAV_TYPE</h2>
  <p class="description">
  </p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">CMD ID</th>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field" id="MAV_TYPE_GENERIC">
     <td class="mavlink_type" valign="top">0</td>
     <td class="mavlink_name" valign="top">MAV_TYPE_GENERIC</td>
     <td class="mavlink_comment">Generic micro air vehicle.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_TYPE_FIXED_WING">
     <td class="mavlink_type" valign="top">1</td>
     <td class="mavlink_name" valign="top">MAV_TYPE_FIXED_WING</td>
     <td class="mavlink_comment">Fixed wing aircraft.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_TYPE_QUADROTOR">
     <td class="mavlink_type" valign="top">2</td>
     <td class="mavlink_name" valign="top">MAV_TYPE_QUADROTOR</td>
     <td class="mavlink_comment">Quadrotor</td>
    </tr>
    <tr class="mavlink_field" id="MAV_TYPE_COAXIAL">
     <td class="mavlink_type" valign="top">3</td>
     <td class="mavlink_name" valign="top">MAV_TYPE_COAXIAL</td>
     <td class="mavlink_comment">Coaxial helicopter</td>
    </tr>
    <tr class="mavlink_field" id="MAV_TYPE_HELICOPTER">
     <td class="mavlink_type" valign="top">4</td>
     <td class="mavlink_name" valign="top">MAV_TYPE_HELICOPTER</td>
     <td class="mavlink_comment">Normal helicopter with tail rotor.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_TYPE_ANTENNA_TRACKER">
     <td class="mavlink_type" valign="top">5</td>
     <td class="mavlink_name" valign="top">MAV_TYPE_ANTENNA_TRACKER</td>
     <td class="mavlink_comment">Ground installation</td>
    </tr>
    <tr class="mavlink_field" id="MAV_TYPE_GCS">
     <td class="mavlink_type" valign="top">6</td>
     <td class="mavlink_name" valign="top">MAV_TYPE_GCS</td>
     <td class="mavlink_comment">Operator control unit / ground control station</td>
    </tr>
    <tr class="mavlink_field" id="MAV_TYPE_AIRSHIP">
     <td class="mavlink_type" valign="top">7</td>
     <td class="mavlink_name" valign="top">MAV_TYPE_AIRSHIP</td>
     <td class="mavlink_comment">Airship, controlled</td>
    </tr>
    <tr class="mavlink_field" id="MAV_TYPE_FREE_BALLOON">
     <td class="mavlink_type" valign="top">8</td>
     <td class="mavlink_name" valign="top">MAV_TYPE_FREE_BALLOON</td>
     <td class="mavlink_comment">Free balloon, uncontrolled</td>
    </tr>
    <tr class="mavlink_field" id="MAV_TYPE_ROCKET">
     <td class="mavlink_type" valign="top">9</td>
     <td class="mavlink_name" valign="top">MAV_TYPE_ROCKET</td>
     <td class="mavlink_comment">Rocket</td>
    </tr>
    <tr class="mavlink_field" id="MAV_TYPE_GROUND_ROVER">
     <td class="mavlink_type" valign="top">10</td>
     <td class="mavlink_name" valign="top">MAV_TYPE_GROUND_ROVER</td>
     <td class="mavlink_comment">Ground rover</td>
    </tr>
    <tr class="mavlink_field" id="MAV_TYPE_SURFACE_BOAT">
     <td class="mavlink_type" valign="top">11</td>
     <td class="mavlink_name" valign="top">MAV_TYPE_SURFACE_BOAT</td>
     <td class="mavlink_comment">Surface vessel, boat, ship</td>
    </tr>
    <tr class="mavlink_field" id="MAV_TYPE_SUBMARINE">
     <td class="mavlink_type" valign="top">12</td>
     <td class="mavlink_name" valign="top">MAV_TYPE_SUBMARINE</td>
     <td class="mavlink_comment">Submarine</td>
    </tr>
    <tr class="mavlink_field" id="MAV_TYPE_HEXAROTOR">
     <td class="mavlink_type" valign="top">13</td>
     <td class="mavlink_name" valign="top">MAV_TYPE_HEXAROTOR</td>
     <td class="mavlink_comment">Hexarotor</td>
    </tr>
    <tr class="mavlink_field" id="MAV_TYPE_OCTOROTOR">
     <td class="mavlink_type" valign="top">14</td>
     <td class="mavlink_name" valign="top">MAV_TYPE_OCTOROTOR</td>
     <td class="mavlink_comment">Octorotor</td>
    </tr>
    <tr class="mavlink_field" id="MAV_TYPE_TRICOPTER">
     <td class="mavlink_type" valign="top">15</td>
     <td class="mavlink_name" valign="top">MAV_TYPE_TRICOPTER</td>
     <td class="mavlink_comment">Octorotor</td>
    </tr>
    <tr class="mavlink_field" id="MAV_TYPE_FLAPPING_WING">
     <td class="mavlink_type" valign="top">16</td>
     <td class="mavlink_name" valign="top">MAV_TYPE_FLAPPING_WING</td>
     <td class="mavlink_comment">Flapping wing</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="MAV_MODE_FLAG" name="ENUM_MAV_MODE_FLAG">MAV_MODE_FLAG</h2>
  <p class="description">These flags encode the MAV mode.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">CMD ID</th>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field" id="MAV_MODE_FLAG_SAFETY_ARMED">
     <td class="mavlink_type" valign="top">128</td>
     <td class="mavlink_name" valign="top">MAV_MODE_FLAG_SAFETY_ARMED</td>
     <td class="mavlink_comment">0b10000000 MAV safety set to armed. Motors are enabled / running / can start. Ready to fly.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_MODE_FLAG_MANUAL_INPUT_ENABLED">
     <td class="mavlink_type" valign="top">64</td>
     <td class="mavlink_name" valign="top">MAV_MODE_FLAG_MANUAL_INPUT_ENABLED</td>
     <td class="mavlink_comment">0b01000000 remote control input is enabled.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_MODE_FLAG_HIL_ENABLED">
     <td class="mavlink_type" valign="top">32</td>
     <td class="mavlink_name" valign="top">MAV_MODE_FLAG_HIL_ENABLED</td>
     <td class="mavlink_comment">0b00100000 hardware in the loop simulation. All motors / actuators are blocked, but internal software is full operational.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_MODE_FLAG_STABILIZE_ENABLED">
     <td class="mavlink_type" valign="top">16</td>
     <td class="mavlink_name" valign="top">MAV_MODE_FLAG_STABILIZE_ENABLED</td>
     <td class="mavlink_comment">0b00010000 system stabilizes electronically its attitude (and optionally position). It needs however further control inputs to move around.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_MODE_FLAG_GUIDED_ENABLED">
     <td class="mavlink_type" valign="top">8</td>
     <td class="mavlink_name" valign="top">MAV_MODE_FLAG_GUIDED_ENABLED</td>
     <td class="mavlink_comment">0b00001000 guided mode enabled, system flies waypoints / mission items.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_MODE_FLAG_AUTO_ENABLED">
     <td class="mavlink_type" valign="top">4</td>
     <td class="mavlink_name" valign="top">MAV_MODE_FLAG_AUTO_ENABLED</td>
     <td class="mavlink_comment">0b00000100 autonomous mode enabled, system finds its own goal positions. Guided flag can be set or not, depends on the actual implementation.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_MODE_FLAG_TEST_ENABLED">
     <td class="mavlink_type" valign="top">2</td>
     <td class="mavlink_name" valign="top">MAV_MODE_FLAG_TEST_ENABLED</td>
     <td class="mavlink_comment">0b00000010 system has a test mode enabled. This flag is intended for temporary system tests and should not be used for stable implementations.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_MODE_FLAG_CUSTOM_MODE_ENABLED">
     <td class="mavlink_type" valign="top">1</td>
     <td class="mavlink_name" valign="top">MAV_MODE_FLAG_CUSTOM_MODE_ENABLED</td>
     <td class="mavlink_comment">0b00000001 Reserved for future use.</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="MAV_MODE_FLAG_DECODE_POSITION" name="ENUM_MAV_MODE_FLAG_DECODE_POSITION">MAV_MODE_FLAG_DECODE_POSITION</h2>
  <p class="description">These values encode the bit positions of the decode position. These values can be used to read the value of a flag bit by combining the base_mode variable with AND with the flag position value. The result will be either 0 or 1, depending on if the flag is set or not.</p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">CMD ID</th>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field" id="MAV_MODE_FLAG_DECODE_POSITION_SAFETY">
     <td class="mavlink_type" valign="top">128</td>
     <td class="mavlink_name" valign="top">MAV_MODE_FLAG_DECODE_POSITION_SAFETY</td>
     <td class="mavlink_comment">First bit:  10000000</td>
    </tr>
    <tr class="mavlink_field" id="MAV_MODE_FLAG_DECODE_POSITION_MANUAL">
     <td class="mavlink_type" valign="top">64</td>
     <td class="mavlink_name" valign="top">MAV_MODE_FLAG_DECODE_POSITION_MANUAL</td>
     <td class="mavlink_comment">Second bit: 01000000</td>
    </tr>
    <tr class="mavlink_field" id="MAV_MODE_FLAG_DECODE_POSITION_HIL">
     <td class="mavlink_type" valign="top">32</td>
     <td class="mavlink_name" valign="top">MAV_MODE_FLAG_DECODE_POSITION_HIL</td>
     <td class="mavlink_comment">Third bit:  00100000</td>
    </tr>
    <tr class="mavlink_field" id="MAV_MODE_FLAG_DECODE_POSITION_STABILIZE">
     <td class="mavlink_type" valign="top">16</td>
     <td class="mavlink_name" valign="top">MAV_MODE_FLAG_DECODE_POSITION_STABILIZE</td>
     <td class="mavlink_comment">Fourth bit: 00010000</td>
    </tr>
    <tr class="mavlink_field" id="MAV_MODE_FLAG_DECODE_POSITION_GUIDED">
     <td class="mavlink_type" valign="top">8</td>
     <td class="mavlink_name" valign="top">MAV_MODE_FLAG_DECODE_POSITION_GUIDED</td>
     <td class="mavlink_comment">Fifth bit:  00001000</td>
    </tr>
    <tr class="mavlink_field" id="MAV_MODE_FLAG_DECODE_POSITION_AUTO">
     <td class="mavlink_type" valign="top">4</td>
     <td class="mavlink_name" valign="top">MAV_MODE_FLAG_DECODE_POSITION_AUTO</td>
     <td class="mavlink_comment">Sixt bit:   00000100</td>
    </tr>
    <tr class="mavlink_field" id="MAV_MODE_FLAG_DECODE_POSITION_TEST">
     <td class="mavlink_type" valign="top">2</td>
     <td class="mavlink_name" valign="top">MAV_MODE_FLAG_DECODE_POSITION_TEST</td>
     <td class="mavlink_comment">Seventh bit: 00000010</td>
    </tr>
    <tr class="mavlink_field" id="MAV_MODE_FLAG_DECODE_POSITION_CUSTOM_MODE">
     <td class="mavlink_type" valign="top">1</td>
     <td class="mavlink_name" valign="top">MAV_MODE_FLAG_DECODE_POSITION_CUSTOM_MODE</td>
     <td class="mavlink_comment">Eighth bit: 00000001</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="MAV_STATE" name="ENUM_MAV_STATE">MAV_STATE</h2>
  <p class="description">
  </p>
  <table class="sortable">
   <thead>
    <tr>
     <th class="mavlink_field_header">CMD ID</th>
     <th class="mavlink_field_header">Field Name</th>
     <th class="mavlink_field_header">Description</th>
    </tr>
   </thead>
   <tbody>
    <tr class="mavlink_field" id="MAV_STATE_UNINIT">
     <td class="mavlink_type" valign="top">0</td>
     <td class="mavlink_name" valign="top">MAV_STATE_UNINIT</td>
     <td class="mavlink_comment">Uninitialized system, state is unknown.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_STATE_BOOT">
     <td class="mavlink_type" valign="top">
     </td>
     <td class="mavlink_name" valign="top">MAV_STATE_BOOT</td>
     <td class="mavlink_comment">System is booting up.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_STATE_CALIBRATING">
     <td class="mavlink_type" valign="top">
     </td>
     <td class="mavlink_name" valign="top">MAV_STATE_CALIBRATING</td>
     <td class="mavlink_comment">System is calibrating and not flight-ready.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_STATE_STANDBY">
     <td class="mavlink_type" valign="top">
     </td>
     <td class="mavlink_name" valign="top">MAV_STATE_STANDBY</td>
     <td class="mavlink_comment">System is grounded and on standby. It can be launched any time.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_STATE_ACTIVE">
     <td class="mavlink_type" valign="top">
     </td>
     <td class="mavlink_name" valign="top">MAV_STATE_ACTIVE</td>
     <td class="mavlink_comment">System is active and might be already airborne. Motors are engaged.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_STATE_CRITICAL">
     <td class="mavlink_type" valign="top">
     </td>
     <td class="mavlink_name" valign="top">MAV_STATE_CRITICAL</td>
     <td class="mavlink_comment">System is in a non-normal flight mode. It can however still navigate.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_STATE_EMERGENCY">
     <td class="mavlink_type" valign="top">
     </td>
     <td class="mavlink_name" valign="top">MAV_STATE_EMERGENCY</td>
     <td class="mavlink_comment">System is in a non-normal flight mode. It lost control over parts or over the whole airframe. It is in mayday and going down.</td>
    </tr>
    <tr class="mavlink_field" id="MAV_STATE_POWEROFF">
     <td class="mavlink_type" valign="top">
     </td>
     <td class="mavlink_name" valign="top">MAV_STATE_POWEROFF</td>
     <td class="mavlink_comment">System just initialized its power-down sequence, will shut down now.</td>
    </tr>
   </tbody>
  </table>
  <h1>MAVLink Messages</h1>
  <h2 class="mavlink_message_name" id="HEARTBEAT" name="HEARTBEAT">HEARTBEAT (<a href="
      #HEARTBEAT">
    #0
   </a>
   )
  </h2>
  <p class="description">The heartbeat message shows that a system is present and responding. The type of the MAV and Autopilot hardware allow the receiving system to treat further messages from this system appropriate (e.g. by laying out the user interface based on the autopilot).</p>
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
     <td class="mavlink_name" valign="top">type</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Type of the MAV (quadrotor, helicopter, etc., up to 15 types, defined in MAV_TYPE ENUM)</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">autopilot</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Autopilot type / class. defined in MAV_AUTOPILOT ENUM</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">base_mode</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">System mode bitfield, see MAV_MODE_FLAGS ENUM in mavlink/include/mavlink_types.h</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">custom_mode</td>
     <td class="mavlink_type" valign="top">uint32_t</td>
     <td class="mavlink_comment">A bitfield for use for autopilot-specific flags.</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">system_status</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">System status flag, see MAV_STATE ENUM</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">mavlink_version</td>
     <td class="mavlink_type" valign="top">uint8_t_mavlink_version</td>
     <td class="mavlink_comment">MAVLink version</td>
    </tr>
   </tbody>
  </table>
 </body>
</html>