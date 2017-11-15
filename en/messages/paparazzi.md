<html>
 <body>
  <h1>MAVLink Include Files</h1>
  <p>
   <strong>
    <em>Including files:</em>common.xml</strong>
  </p>
  <h1>MAVLink Protocol Version</h1>
  <p>This file has protocol version: 3. The version numbers range from 1-255.</p>
  <h1>MAVLink Type Enumerations</h1>
  <h1>MAVLink Messages</h1>
  <h2 class="mavlink_message_name" id="SCRIPT_ITEM">SCRIPT_ITEM (<a href="#SCRIPT_ITEM">
    #180
   </a>
   )
  </h2>
  <p class="description">Message encoding a mission script item. This message is emitted upon a request for the next script item.</p>
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
     <td class="mavlink_name" valign="top">target_system</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">System ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_component</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Component ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">seq</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Sequence</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">name</td>
     <td class="mavlink_type" valign="top">char[50]</td>
     <td class="mavlink_comment">The name of the mission script, NULL terminated.</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="SCRIPT_REQUEST">SCRIPT_REQUEST (<a href="#SCRIPT_REQUEST">
    #181
   </a>
   )
  </h2>
  <p class="description">Request script item with the sequence number seq. The response of the system to this message should be a SCRIPT_ITEM message.</p>
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
     <td class="mavlink_name" valign="top">target_system</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">System ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_component</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Component ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">seq</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Sequence</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="SCRIPT_REQUEST_LIST">SCRIPT_REQUEST_LIST (<a href="#SCRIPT_REQUEST_LIST">
    #182
   </a>
   )
  </h2>
  <p class="description">Request the overall list of mission items from the system/component.</p>
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
     <td class="mavlink_name" valign="top">target_system</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">System ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_component</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Component ID</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="SCRIPT_COUNT">SCRIPT_COUNT (<a href="#SCRIPT_COUNT">
    #183
   </a>
   )
  </h2>
  <p class="description">This message is emitted as response to SCRIPT_REQUEST_LIST by the MAV to get the number of mission scripts.</p>
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
     <td class="mavlink_name" valign="top">target_system</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">System ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">target_component</td>
     <td class="mavlink_type" valign="top">uint8_t</td>
     <td class="mavlink_comment">Component ID</td>
    </tr>
    <tr class="mavlink_field">
     <td class="mavlink_name" valign="top">count</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Number of script items in the sequence</td>
    </tr>
   </tbody>
  </table>
  <h2 class="mavlink_message_name" id="SCRIPT_CURRENT">SCRIPT_CURRENT (<a href="#SCRIPT_CURRENT">
    #184
   </a>
   )
  </h2>
  <p class="description">This message informs about the currently active SCRIPT.</p>
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
     <td class="mavlink_name" valign="top">seq</td>
     <td class="mavlink_type" valign="top">uint16_t</td>
     <td class="mavlink_comment">Active Sequence</td>
    </tr>
   </tbody>
  </table>
 </body>
</html>