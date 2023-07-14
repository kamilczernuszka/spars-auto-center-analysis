# spars-auto-center-analysis

## SPARSE System Requirements Analysis for Auto Center
In this repository, the functional and non-functional requirements of the designed system for a fictitious company were developed. The Auto Center company is an organization where the process of repairing passenger cars takes place. Workplace
is headquartered at 5 Poziomkowa Street in Zielona Góra. Two people work in the company.

### Functional Requirements

#### ID: WYMF_1
- Name: Service Cost Calculation Process
- Priority: High
- Business Process: "Preliminary Service Cost Calculation"
- Description: The electrician should be able to calculate the preliminary cost of a service based on the service price list stored in the system.

#### ID: WYMF_2
- Name: Archiving Management
- Priority: High
- Business Process: "Order Document Archiving"
- Description: The manager should have access to the option of archiving repair protocols in electronic form.

#### ID: WYMF_3
- Name: Order Document Preparation
- Priority: High
- Business Process: "Order Document Preparation"
- Description: The electrician should be able to generate an order document based on the provided order information.

#### ID: WYMF_4
- Name: Order Document Printing
- Priority: High
- Business Process: "Order Document Printing"
- Description: The electrician should be able to print the generated order document.

#### ID: WYMF_5
- Name: Repair Protocol Completion
- Priority: High
- Business Process: "Repair Protocol Preparation"
- Description: The electrician should be able to fill out a document called the repair protocol, which documents the performed actions and identified cause of the fault.

#### ID: WYMF_6
- Name: Repair Protocol Review
- Priority: High
- Business Process: "Repair Protocol Review"
- Description: The electrician should be able to access archived repair protocols for review.

#### ID: WYMF_7
- Name: Invoice Generation
- Priority: High
- Business Process: "Invoice Generation"
- Description: The electrician should be able to generate an invoice.

### Non-functional Requirements

#### ID: NWYMF_1
- Name: Information Collection - Tablet
- Priority: Medium
- Business Process: "Collection of necessary information from the client"
- Description: The information collection should be done using a tablet device located in the workshop.

#### ID: NWYMF_2
- Name: Order Document Format
- Priority: Medium
- Business Process: "Order Document Preparation"
- Description: The order document should be generated in PDF format.

#### ID: NWYMF_3
- Name: Invoice Format
- Priority: Medium
- Business Process: "Invoice Generation"
- Description: The invoice should be generated in PDF format.

#### ID: NWYMF_4
- Name: Repair Protocol Format
- Priority: Medium
- Business Process: "Repair Protocol Preparation"
- Description: The repair protocol should be stored in a text-based XML format that allows reading it without relying on the system.

  ## Business process diagram

  A diagram of the business process is inserted below, it is also in the file spars-auto-center-analysis.bpmn

![1](https://github.com/kamilczernuszka/spars-auto-center-analysis/assets/139373087/5af2a818-f3a1-4622-9b63-69fa39375187)

# Running BPMN in Camunda Modeler

To run a spars-auto-center-analysis.bpmn file in Camunda Modeler, follow these steps:

1. Download and install Camunda Modeler: Visit the official Camunda website (https://camunda.com/download/modeler/) to download the Camunda Modeler application compatible with your operating system.

2. Launch Camunda Modeler: After installing Camunda Modeler, open the application on your computer.

3. Open the BPMN file: In Camunda Modeler, go to "File" and select "Open File". Browse to the location where your BPMN file is stored and select it. The BPMN file will be loaded into the Camunda Modeler interface.

4. Execute the BPMN process in Camunda Engine: Camunda Modeler is primarily used for modeling and designing BPMN processes. To execute and monitor the BPMN process, you will need to deploy and run it in the Camunda Engine, which is a separate runtime environment provided by Camunda.

## License

This project is licensed under the [MIT License](LICENSE).

You are free to use, modify, and distribute this project as needed.
