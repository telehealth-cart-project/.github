# Telehealth Cart: ML Based Screening
<table>
  <tr>
    <td width="40%">
      <img src="https://github.com/user-attachments/assets/3a1fc2f1-dc31-48b3-a7c2-d80713f0222a" width="100%">
    </td>
    <td width="60%" valign="top">
      <h2>Overview of Project</h2>
      <p>
        This project aims to improve emergency response and healthcare delivery during 
        public health crises by automatic basic patient screening and triage. The system
        is designed to support patient flow, identify potentially critical conditions, and help 
        relief personnel prioritize patients who may require urgent treatment. 
      </p>
      <p>
        The telehealth cart integrates modular biosensors, a patient graphical user interface,
        and a machine learning-based triage classification. Its modular design allows sensor 
        components to be replaced, upgraded, or adapted for different emergency scenarios and 
        healthcare environments. The overall goal is to reduce the burden of repetitive screening
        tasks on healthcare personnel while supporting faster and more informed triage decisions 
        during a crises siutation. 
      </p>
    </td>
  </tr>
</table>

<h2>Project Repositories</h2>

<p>
The Telehealth Cart project is organized across several repositories.
Development repositories are currently private, so access is limited to authorized collaborators.
</p>

<table>
<tr>
<td valign="top">
<h3><a href="REPO-LINK-HERE">MDS-capstone</a></h3>
<p>
Contains the original 2025–2026 Telehealth Cart capstone code and serves as the
foundation for the current project.
</p>
<p><strong>Role:</strong> Original capstone development</p>
</td>
</tr>
</table>

<br>

<table>
<tr>
<td valign="top">
<h3><a href="REPO-LINK-HERE">telehealth-cart</a></h3>
<p>
Contains the current development code for the Telehealth Cart as the project continues
beyond the original capstone implementation.
</p>
<p><strong>Role:</strong> Current system development</p>
</td>
</tr>
</table>

<br>

<table>
<tr>
<td valign="top">
<h3><a href="REPO-LINK-HERE">references</a></h3>
<p>
A collection of reference code, examples, documentation, and other resources used to
support development of the Telehealth Cart.
</p>
<p><strong>Role:</strong> Technical references and examples</p>
</td>
</tr>
</table>

<br>

<table>
<tr>
<td valign="top">
<h3><a href="REPO-LINK-HERE">project-notes</a></h3>
<p>
A working space for project notes, documents, smaller development materials, and
discussion related to ongoing Telehealth Cart work.
</p>
<p><strong>Role:</strong> Project documentation and collaboration</p>
</td>
</tr>
</table>


<h2>Current Developments</h2>

<p>
The primary focus of current development is improving the ML
architecture so that the telehealth cart can function as a truly modular
screening platform.
</p>

<table>
<tr>
<td valign="top">
<h3>Modular Machine Learning Architecture</h3>
<p>
The current ML system must be expanded so that triage classification
can remain functional even when the available sensor configuration changes.
Rather than requiring one fixed set of inputs, the goal is to train and organize
models so the system can adapt when sensors are unavailable, removed, added, or
replaced.
</p>

<p>
This is especially important for a modular telehealth platform, where different
deployments may use different combinations of sensors. The ML pipeline therefore
needs to support multiple valid input configurations while maintaining reliable
triage performance.
</p>
</td>
</tr>
</table>

<br>

<table>
<tr>
<td valign="top">
<h3>Expanded Training Data</h3>
<p>
A major limitation of the original capstone project was access to sufficiently
large and appropriate clinical datasets for training and validating the triage
models. Continued development will require access to more representative patient
data containing a wider range of vital sign combinations, triage outcomes, and
clinical scenarios.
</p>

<p>
Additional data will allow the models to be trained and validated across different
sensor combinations rather than around a single fixed configuration, which is
necessary for reliable modular operation.
</p>
</td>
</tr>
</table>

<br>

<table>
<tr>
<td valign="top">
<h3>Sensor Integration</h3>
<p>
Future development will also focus on separating the ML pipeline
from individual sensor hardware. Sensors that measure the same physiological
variable should be replaceable without requiring major changes to the overall
triage system.
</p>

<p>
This requires standardized data handling, preprocessing, and interfaces so that
the ML models operate on validated physiological measurements rather than being
tied to one specific device or manufacturer.
</p>
</td>
</tr>
</table>

<br>

<table>
<tr>
<td valign="top">
<h3>Accessibility & User Interface Development</h3>
<p>
The patient and provider interfaces will continue to be refined with a focus on
accessibility, including expanded language support and more intuitive workflows
for users with limited training.
</p>
</td>
</tr>
</table>

<br>

<table>
<tr>
<td valign="top">
<h3>Expanded Screening Capabilities</h3>
<p>
Additional screening methods are being considered beyond the original vital sign
pipeline. Potential future work includes computer vision-based assessment of
patient information such as respiratory characteristics, temperature, and other
observable indicators.
</p>
</td>
</tr>
</table>

<br>

<table>
<tr>
<td valign="top">
<h3>New Clinical Use Cases</h3>
<p>
The modular platform is also being evaluated for applications beyond disaster
relief, including screening in rural clinics and other healthcare environments
with limited staff or resources.
</p>
</td>
</tr>
</table>
