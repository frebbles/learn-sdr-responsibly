## Learn SDR responsibly

A series of GNU Octave scripts I have developed over time to assist my understanding of SDR techniques at their most low level.

I have prioritised simplicity and base techniques and avoid using 'black box' functions in the interest of promoting understanding what each stage of SDR processing is actually doing.

# Getting started

Files are built using GNU Octave (>5.2). 

You will need to install/run the following commands in Octave to install required packages.
    pkg install -forge control
    pkg install -forge signal
    pkg install -forge communications

# Usage

Set the base directory for Octave to this repo.

Open and run files.

The Octave Files have been produced to be produced as reports with LaTeX and graphics inline, to produce the reports, from the base directory, run:

    publish('ModemQAM.m', 'html');