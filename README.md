# SmartSEM-Imaging-Project
Jessika Jimenez

University of Utah
ECE 3970 (Undergraduate Research)
.
. 
Project for SmartSEM for the GeminiSEM

Information: "We are trying to do targeted reconstruction of sections from cultured neurons.  We are using a scanning electron microscope, so collecting images is really slow.  To reconstruct 20 synapses takes > 8 hours of scope time, so we usually set it up for overnight.  We want to define the location of synapses in one section and have the SEM find the same sites in neighboring sections.  The microscope will then image that region at high resolution for every section.   In more detail than you probably care but a student might: To generate a ribbon of sections, we cut 50nm sections from plastic blocks.  Each section is a trapezoid of about 1mm x 1mm.  The sections come off the knife as a ribbon of about 20 sections (they usually curve slightly because the base and top of the trapezoid are not perfect).  We image the whole ribbon at low magnification (which is about 20 - 50  mm in length).  (see figure)  We then go to the middle section and image~10-20 synapses at high magnification, the field size is about 5 um X 5 um.  This provides us with high mag X and Y coordinates within the trapezoid of that middle section (X’s on the figure).   It is a pretty simple problem:  The outline of the ribbon can serve as a template for the X-Y coordinates for the corners of each section.  We just need to translate the X-Y coordinate of each synapse from the middle section, to the same positions on the other sections.  That will then provide the X-Y coordinates that the microscope can locate and image at high magnification.   But we need programming skills to calculate all of the X-Y positions so the computer can tell the microscope where to image."
