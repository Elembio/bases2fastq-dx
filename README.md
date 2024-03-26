**bases2fastq-dx** is a DNAnexus applet that can be used to build a DNAnexus app and workflow to demultiplex the raw data produced by the Element AVITI™ System using the Bases2Fastq Software. Bases2Fastq processes sequencing data and converts base calls into FASTQ files. During a sequencing run, the Element AVITI™ System records base calls and associated quality scores (Q-scores) in bases files. Bases2Fastq converts the bases files into the FASTQ file format for secondary analysis with the FASTQ-compatible software of your choice. 

- The [Bases2Fastq Documentation](https://docs.dev.elembio.io/docs/bases2fastq/introduction/) has detailed execution information for changing parameters.
- The [Run Manifest Documentation](https://docs.dev.elembio.io/docs/run-manifest/) has detailed information for resetting demultiplexing settings, controlled by the input Run Manifest.
  
Bases2fastq-dx enables you to run Bases2Fastq on in a DNAnexus project.


## dx build commands

```
dx build -f bases2fastq/
```

## Run the applet 
```
dx run bases2fastq-dx -i analysis_directory={your-projectid}:/{path to run directory}
```

## License
Bases2Fastq use subject to license available at go.elembio.link/eula.
