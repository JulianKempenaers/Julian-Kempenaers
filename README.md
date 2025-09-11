
# Julian Kempenaers
Hello, I'm Julian,

I'm a Data Analyst focused on automation and data solutions. I build custom tools and deliver data-driven solutions for research labs and businesses. I focus on automating complex workflows, enabling real-time experimental data analysis, and creating scalable tracking and monitoring systems. I help turn raw data into clear insights that improve both experiments and business decisions. 

## My areas of expertise:
### :computer: Languages
- Python
- R
- SQL
- MATLAB

### :bar_chart: Data Analysis:
- Data Visualisation - creating clear and informative graphics from data
- Statistical analysis - applying statistical methods to interpret data
- Data Preprocessing - cleaning, transforming and preparing data for analysis
- Database Querying (SQL) - writing queries for optimal data extraction

>Project examples:<br>
> [`Data-driven Sales Recommendations`](#data-driven-sales-recommendations)<br> 
> [`Business analaysis with SQL queries`](#business-analaysis-with-sql-queries) <br>
> [`Statistical Analysis of Tag Scanability`](#statistical-analysis-of-tag-scanability-under-obstructed-conditions) <br>
> [`Instant electrophysiology Data analysis & visualisation tool`](#instant-electrophysiology-data-analysis--visualisation-tool) <br>


### :hammer_and_wrench: Programming and tool development:

Software development for Experimental Systems - building custom tools for research and experimental setups, such as:
- Automated Experimental Reporting: Generating real-time visual summaries of experimental data.
- Efficient data storage techniques: developing custom data compression and storage solutions for repetitive video files

>Project examples:<br>
>[`Real-time STag detector`](#real-time-stag-detector)<br>
>[`Sparse Motion Capture`](#sparse-motion-capture)<br>
>[`Advanced Multi-Modal Animal tracking software`](#advanced-multi-modal-animal-tracking-software)<br>
>[`Raspberry Pi Cluster Synchronisation & Control`](#raspberry-pi-cluster-synchronisation--control)<br>
>[`Post-recording STat Detector`](#post-recording-stag-detector)<br>

---

# :open_file_folder: Projects

---

## Sparse Motion Capture
Objective: Develop a **real-time video capture tool** in **Python** for **Raspberry Pi** using **Picam2**, which stores only moving pixels in **sparse matrix format** (BSR) to drastically reduce data file sizes of long-duration footage with static backgrounds.
- Developed in **Python**
- **Computer vision** (OpenCV, motion ROI detection)
- Real-time frame processing using **multiprocessing** with adaptive **queue** control
- **Custom data compression** for memory efficient storage
- Included a utility to convert compressed data (.npz) back to video (.mp4) format for playback. 
>:link: [click here to view project](https://github.com/JulianKempenaers/Sparse-Motion-Capture/blob/main/README.md)
### Non-technical summary
Built a smart video recording system that only saves parts of the video where there’s movement. This reduces storage needs and helps researchers focus on important actions during experiments.

---

## Data-driven sales recommendations 
Objective: Create a **custom metric** to evaluate the **sales strategy performance**. 
- **Data cleaning**
- **Statistical analysis**
- **Data visualization**
- **Modeled outcomes**
- Performed in **R**
- **Jupyter Lab**
- Delivered actionable **business recommendations.**
>:link: [click here to view project](https://github.com/JulianKempenaers/Data-Driven-Sales-Recommendations/blob/main/README.md)

### Non-technical summary:
Created a custom measurement to evaluate how well a company’s sales strategies work by cleaning and analyzing sales data. This helped the business make better decisions to improve sales performance.

--- 

## Real-time STag Detector
Objective: Develop a tool that performs **real-time detection and tracking** of specialized QR codes, with a **live video stream overlay**. Ideal for **motion tracking** in experimental setups
- Developed in **python**
- Built for **Raspberry Pi** with up to two **Picam2** cameras
- Inlcudes a **Graphical User Interface (GUI)** for adjusting detection parameters and optional **video saving**.
- Can run on two cameras simultaneously using **multithreading** for concurrent frame capture and processing.
- Supports **colour-coded tracking** of recent tags.
>:link: [click here to view project](https://github.com/JulianKempenaers/real-time-tag-detector/blob/main/README.md)
### Non-technical summary
Developed software that quickly spots special QR-like codes on animals during experiments, tracking their movement live to help scientists understand behavior in real time.

---

## Business analaysis with SQL queries
Objective: Analyzed and cleaned a grocery store product dataset using SQL to support price range optimization by identifying sales and pricing trends across categories and brands.
- **SQL**: complex queries, subqueries, CTEs, aggregation, ordering, filtering
- **Data Cleaning**: handling missing values, normalization, string functions, regex
- **Exploratory Data Analysis**: price ranges, category trends, brand comparisons
- Price and Sales insights 
- **Window/Aggregate Functions**
- Conditonal logic and imputation
- **PostgreSQL** functions: REGEXP_REPLACE, ROUND, CAST, etc.
>:link: [click here to view project](https://github.com/JulianKempenaers/business-analysis-with-sql-and-data-cleaning/tree/main)

### Non-technical summary
Analyzed grocery store product data to find trends in sales and prices, helping to optimize pricing strategies and improve overall business performance.

---

## Statistical Analysis of Tag Scanability under obstructed conditions
Objective: Optimisation of tag detection through netting using data analysis and statistical modeling. 
- **Python**: pandas, statistical testing (Kruskal-Wallis, Mann-Whitney U)
- **data visualization** (matplotlib)
- Explored how camera aperture and net height affect tag scanability to inform practical recommendations.
>:link: [click here to view project](https://github.com/JulianKempenaers/tag-scanability-analysis/blob/main/README.md)
### Non-technical summary
Studied how factors like net height and camera settings affect the ability to detect tracking tags, to recommend the best setup for accurate data collection during experiments.

---

## Post-recording STag Detector
Objective: Develop a tool that performs **post-processing** detection and tracking of pecialized of QR codes. Ideal for **post-recording motion tracking** experimental setups.
- Developed in **Python**
- Designed to work with **sparse matrix video formats** captured via my [**Sparse Motion Capture**](#sparse-motion-capture).
- Includes a **Graphical User Interface (GUI)** for adjusting detection parameters and optional **video saving**.
- Supports **colour-coded tracking** of recent tags.
>:link: [click here to view project](https://github.com/JulianKempenaers/STag-detector-post-recording/blob/main/README.md?plain=1)

### Non-technical summary
Created a tool to find and track special QR-like codes in recorded videos after the experiment, making it easier to analyze animal movement without needing everything in real time.

---

# Currently working on:

## Instant electrophysiology Data analysis & visualisation tool
Developing an automated, real-time data processing tool for electrophysiological experiments, enabling **immediate insight** into neuron activity post-stimulus presentation
- Addreses the critical experimental constraint of time-sensitive seal quality degradation by delivering **near-instantaneous data visualisation** to optimise experimental decisions and data quality
- Built in **Matlab** for signal processing, data analytics and interactive visualisation **Graphical User Interface** to accelerate experimental workflows and increase throughput 

## Advanced Multi-Modal Animal tracking software
- Developing a **hybrid tracking system** that uses **tag detection as reliable anchors** (~10-50% detection rate), combined with **motion-based interpolation** and **animal shape detection** to maintain continuous tracking even when tags are temporary occluded or undetected.
- Implements **frame-by-frame tracking**, blending precise tag-based localisation with predictive tracking methods to fill in the gaps.
- Integrates 12 high-resolution video tiles into a single unified large-scale field of view, enabling comprehensive spatial coverage of animal movement
- Built in **Python** with multiprocessing efficient processing and scalable performance.

## Raspberry Pi Cluster Synchronisation & Control
Designing a networked system to coordinate 24 Raspberry Pis for simultaneous script execution, enabling precise multi-device motion capture experiments
- Includes a **daemon service** on each Pi to receive and respond to commands via an **MQTT messaging broker**, allowing remote control and synchronisation. E.g. all Raspberry Pi's could start executing the  [sparse motion capture](https://github.com/JulianKempenaers/Sparse-Motion-Capture/blob/main/README.md) script simultaneously. 
- Implements **time synchronisation** using a Synology NAS as an **NTP server** to keep all devices' clocks aligned without internet access.
- **Tools & technologies**: Bash scripting, Python, MQTT protocol, Distributed system design.

---


Please feel free to get in touch at:

- juliankempenaers@gmail.com
- https://www.linkedin.com/in/juliankempenaers/

[Click here to view my publications](https://orcid.org/0000-0002-0059-1045)
