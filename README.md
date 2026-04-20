# sqlmap-multi

This script is a parallel SQLMap execution manager that splits a large list of URLs into multiple parts and 
runs SQLMap on each part simultaneously. Here's what it does:<br/><br/>



### File Splitting:

  * Takes your input file of URLs and divides it into multiple roughly equal parts


### Parallel Processing: 

  * Launches multiple SQLMap processes simultaneously, each working on a different part of the URL list



### Real-time Monitoring:

  * Displays a live dashboard showing the status of all started processes
  * Shows running time, output file size, and completion status for each process
  * Features smooth spinner animations for active processes



### Vulnerability Detection:

  * Monitors SQLMap's results CSV file in real-time
  * Scans for new vulnerabilities every 60 seconds
  * Displays any newly discovered vulnerabilities as they're found


### User Controls:

  * Press ESC to interrupt all processes at any time
  * Shows a countdown until the next vulnerability check


### Output Management:

  * Creates separate output files for each process
  * Provides a final summary of all results


<br/><br/>The script is designed to make SQLMap scanning more efficient by parallelizing the work and providing real-time feedback on both the scanning progress and any 
vulnerabilities discovered.
