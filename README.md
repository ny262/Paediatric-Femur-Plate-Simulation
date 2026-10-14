<style>
  body {
    background-color: #020035;
    color: #e2e8f0;
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif; 
    line-height: 1.5;
    padding: 20px;
  }
  table {
    border-collapse: collapse; 
    width: 80%; 
    border: 1.5px solid #21262d; 
    background-color:#020035;">
    margin-bottom: 15px
  a {
    color: #00f0ff;          
    text-decoration: none;
    font-weight: bold;
  }
   a:hover {
    color: #ffffff;          
    text-decoration: underline; 
  }
   th, td {
    border: 1.5px solid #21262d;
  }
</style>

# Paediatric Femur Plate Simulation

The objective of this CAD project was to design a fracture plate tailored to the anatomy of a paediatric femur, which differs significantly from a mature femur. Design choices were made with both physiology and surgical usability in mind.

Designed for a 35 cm femur, this plate corresponds to the typical anatomy of an 8-to 9-year-old child [1]. A child in this age range typically weighs between 25 to 29 kilograms [2] [3]. The implant was designed for the walking forces of a 29 kg child, calculated by downscaling multi-axis adult gait telemetry data, with a safety factor of 2.0 [4].

The implant architecture is explicitly engineered to navigate the clinical boundaries of paediatric anatomy, maximising mechanical stabilisation while preserving natural bone healing mechanisms.

<table>
  <tr>
    <th>Implant Feature</th>
    <th>CAD Reference</th>
  </tr>
    <td>
      <h3> Distal Anchor Configuration </h3>
      <ul>
        <li> <strong>Maximised Anchor Space:</strong> Fits the most screws securely within the small area above the growth plate. </li>
        <li> <strong>Torsional Resistance:</strong> The triangular layout stops the bone from twisting. </li>
        <li> <strong>Fixation Stability:</strong> Spreads the 29 kg scaled child forces evenly to avoid damaging soft paediatric bone. </li>
      </ul>
    </td> 
  <tr>
</table>
