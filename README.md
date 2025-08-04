**POWER SYSTEM FAULT DETECTION**

The modern power distribution system is a critical infrastructure that demands high reliability, efficiency, and real-time responsiveness. Faults such as **line-to-ground (LG), line-to-line (LL), double line-to-ground (DLG), and three-phase faults can severely impact the stability of the power grid, cause equipment damage, and lead to significant power outages.

Despite significant progress in power system monitoring and automation, there is currently no widely adopted intelligent solution that can accurately and rapidly detect and classify all types of faults in a power distribution system using real-time electrical measurements.

Most existing fault detection techniques rely on manual inspection, fixed threshold rules, or signal-based methods, which are:

* Time-consuming and unsuitable for real-time fault handling
* Error-prone, especially in noisy environments or complex grid topologies
* Not scalable, as they require manual tuning for each specific network scenario

This lack of a robust, automated, and scalable fault diagnosis system poses a major risk to grid reliability, safety, and recovery time during failures.

**Project Goal**

This project aims to bridge that gap by developing a machine learning-based solution capable of:

* Continuously monitoring real-time electrical parameters (voltage and current phasors)
* Accurately detecting the presence of a fault
* Classifying the fault type (e.g., LG, LL, DLG, or 3-phase)
* Providing timely alerts for proactive decision-making by grid operators
