  > Answer Q1
  ***
    event loop allows nodeJS to perform none blocking I/O operations 
    #  IO Queue:-involve external computer devices like read write file operations,network operations etc...
    #  Timer Queue:-setTimeout(),setInterval()are added to the timer queue
    #  MicroTaskQueue:-This queue is broken down into 2 queues process.nextTick and promises.
    #  Check Queue:-also known as immediate queue excuted immediately check the call stack if it is idle .setImmeidate is here
    #  Close Queue :- Stores functions that are associated with close event operations one e.g is stream 
  ***

  >Answer Q2

  ***

    process.nextTick()  
    #  Has higher priority  over setImmediate .Instead of the "immediate queue" the callbacks are quedued in the "next tick queue".
    setImmediate()
    # is excuted in the check handler phase of the event loop

  ***
  >Answer Q3

  ***
  #  Some of  the Core Modules in node  are
  <ol>
  <li>url</li>
  <li>path</li>
  <li>fs</li>
  <li>http</li>
  <li>queryString</li>
 
 
  ***
    ***
  #  Some of  the node global objects  are
   <ol>
  <li>__filename</li>
  <li>setTimeout()</li>
  <li>clearTimeout()</li>
  <li>__dirname</li>
    <li>setInterval()</li>

  ***