# Synthetic Data

**Github**: [https://github.com/KlinterAI/SAS-SQL-Code-Management](https://github.com/KlinterAI/SAS-SQL-Code-Management)

Synthetic Data is used to demonstrated an Operational efficiency through Construction Site Monitoring. 

The 3 major outcomes of the purpose of Synthetic Data is to engage in:
- Time of Activity Measurement 
- Activity-Codes Recognition 
- Incident Monitoring

### Typical Incidents at Construction Site
A list of incidents at the Construction Site is given here corresponding to: 
- Delays
- Issues
- Repairs
- Risk
- Incidents, and
- Other Issues

![Incidents at Construction Site](https://live.staticflickr.com/65535/53047792849_4e27ed3b50.jpg)

With Activity Recognition: A List of such Activities are listed as:
- Soil Extraction
- Dropping and Loading
- Picking
- Driving and Earthmoving
- Picking

![activity-recognition Activities](https://live.staticflickr.com/65535/53093167718_4460306bc9_b.jpg)

These activities can be collectively classified as Earth-moving, as per the Gantt Chart Below:

![Gantt Chart of Activities Recognized](https://live.staticflickr.com/65535/53049092706_248fa179ec_h.jpg)

### Pathways to Costing
Once the material purchase order database including other purchase orders are scheduled in the plan, the costing performed towards the minimization of material wastage impacts the start of the project cycle to the site work. 

By impacting the costing within the Procurement Department and the Construction Site Work, there is transfer of information between departments. This improves error-checking and validation. It also allows the Site Project Manager to schedule imports appropriately. 

![Pathways to Costing](https://live.staticflickr.com/65535/52802281847_f7bec60265_h.jpg)

### Operational Time and Analysis
Percentage contribution: is relevant to the time taken:
- Relevant to each Risk detected by EquipAny mobile-app
- At every risk/issue into the register, the object or a delay recorded leading to the risk/issue, is also part of the register

![Delays and Issues by Objects Detected](https://live.staticflickr.com/65535/53049511255_ac1623d770_b.jpg)

![Risk and Incidents Distribution in Time](https://live.staticflickr.com/65535/53049511260_193d3c6d87_b.jpg)

#### 1. Synthetic Data Generated using [mockaroo.com](mockaroo.com)

**IoT.csv**

The IoT Metadata that helps us understand the Operational Time of each activity when connected to the IoT Metadata relationships.

| SERIAL_NO | EPC_NO                       | MANUFACTURER |
|-----------|------------------------------|--------------|
| 1         | EPC-2345  | Tagcat       |
| 2         | EPC-2345  | Vinder       |
| 3         | EPC-8890  | Omba         |
| 4         | EPC-0987  | Divape       |
| 5         | EPC-4563  | Voonix       |
| 6         | EPC-4563  | Photojam     |
| 7         | EPC-6839  | Rhynyx       |
| 8         | EPC-0385  | Wikizz       |
| 9         | EPC-4529  | Janyx        |
| 10        | EPC-4529 | Kwilith      |

#### 2. Synthetic Data Generated using [mockaroo.com](mockaroo.com)

**GENERAL.csv**

The entire data representing the IoT Database in an Un-normalized form. 

| SERIAL_NO | MATERIAL_PO | EQUIPMENT_ID | MANUFACTURER | EPC_NO                       | SNMP_TOKEN      | ACTIVITY_ID                              |
|-----------|-------------|--------------|--------------|------------------------------|-----------------|------------------------------------------|
| 1         | 1           | 8896445922   | Tagcat       | EPC-2345  | 11.136.66.28    | 7-100 -   Damproofing and Waterproofing  |
| 2         | 1           | 1713765551   | Vinder       | EPC-2345  | 2.173.141.119   | 2-625 -   Retaining Wall Drainage Piping |
| 3         | 0           | 4586149221   | Omba         | EPC-2345  | 171.90.163.68   | 13-260 -   Sludge Conditioning Systems   |
| 4         | 0           | 6752521468   | Divape       | EPC-2345  | 133.192.83.143  | 15-200 -   Process Piping                |
| 5         | 0           | 384443575    | Voonix       | EPC-4529  | 142.81.68.233   | 9-600 -   Flooring                       |
| 6         | 0           | 4965364163   | Photojam     | EPC-4529  | 182.34.205.236  | 1-530 -   Temporary Construction         |
| 7         | 0           | 8806156691   | Rhynyx       | EPC-4529  | 197.136.85.223  | 11-050 -   Library Equipment             |
| 8         | 1           | 3573402445   | Wikizz       | EPC-4529  | 209.218.86.251  | 10-750 -   Telephone Specialties         |
| 9         | 1           | 9942900861   | Janyx        | EPC-4563  | 207.142.0.216   | 2-823 -   PVC Fences and Gates           |
| 10        | 0           | 4151283307   | Kwilith      | EPC-4563 | 223.170.137.108 | 9-100 -   Metal Support Assemblies       |

#### 3. Synthetic Data Generated using [mockaroo.com](mockaroo.com)

**IoT Cost Code.csv**

The cost-codes of the IoT devices in the machinery. 

| ID | ActivityCode | TimeDetectionStart           | Days             |    |
|----|--------------|------------------------------|------------------|----|
| 1            | 16-500 - Lighting            | 10/01/2023 09:20 | 10 |
| 9            | 2-300 - Earthwork            | 19/01/2023 09:20 | 15 |
| 17           | 2-240 - Dewatering           | 31/01/2023 09:20 | 14 |
| 25           | 11-190 - Detention Equipment | 12/02/2023 09:20 | 17 |
| 33           | 17-020 - Insurance           | 24/02/2023 09:20 | 13 |
| 41           | 2-220 - Site Demolition      | 08/03/2023 09:20 | 13 |



> Written with [StackEdit](https://stackedit.io/).
