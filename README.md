# devcs_sample_hudsonjobs

By following below steps , you can import the sample jobs with your specific environment values set.

1. Download the code from GitHub as a zip file.
2. Extract configure-exported-jobs.zip from the downloaded zip file and import that configure-exported-jobs.zip to Developer Cloud using "Administration -> Job Import" .
2. In the Developer Cloud "Build", enable job 'configure-exported-jobs' as it is disable when imported.
3. Execute job 'configure-exported-jobs' . In the job parameter dialog, specify the zip file downloaded at step1 for the jobzip file parameter.
   Enter your environment values for all other job parameters. 
   Leaving parameter as blank is ok, but you will need to input the parameter when executing the sample jobs.
4. The job execution will output a file named 'configured-jobs.zip' as archive. Download this file.
5. From Developer Cloud "Administration -> Job Import" , import that 'configured-jobs.zip'.
