insilico - Neuronal Simulation Library
======================================

Official homepage: http://www.iiserpune.ac.in/~collins/insilico/

Install
=======

Please refer to doc/INSTALL file.

Build
=====

Clone the source and run the following commands on terminal.

   make SOURCE="path/to/source/file/with/main_function.cpp"

Execute
=======

Run the following command on terminal to execute the code.

  insilico.out -o<output_file>.csv -n<neuron_file.isf> -s<synapse_file.isf> -e<external_file.isfc>

  Options:
    -o   Output file
    -n   Neuron configuration file
    -s   Synapse configuration file (optional)
    -e   External current configuration file (optional)

  No space allowed between option and its value.

* Linux / Mac OS

  ./insilico.out -o<outputfile.csv> -n<neuron_file.isf> [-s<synapse_file.isf>] [-e<external_current.isfc>]

* Windows

  .\insilico.out -o<outputfile.csv> -n<neuron_file.isf> [-s<synapse_file.isf>] [-e<external_current.isfc>]

Please read doc/FILES file for details about the input and output files and their formats.

License
=======

This simulator library is licensed under GNU GPLv3 which is described in LICENSE file found in home directory of this project.
