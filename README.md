this code runs on comet
the local.out file looks like tis:

2018-10-20 00:24:41,541 WARN  [main] util.NativeCodeLoader (NativeCodeLoader.java:<clinit>(62)) - Unable to load native-hadoop library for your platform... using builtin-java classes where applicable
2018-10-20 00:24:41,805 INFO  [main] Configuration.deprecation (Configuration.java:warnOnceIfDeprecated(1049)) - session.id is deprecated. Instead, use dfs.metrics.session-id
2018-10-20 00:24:41,807 INFO  [main] jvm.JvmMetrics (JvmMetrics.java:init(76)) - Initializing JVM Metrics with processName=JobTracker, sessionId=
2018-10-20 00:24:42,155 WARN  [main] mapreduce.JobSubmitter (JobSubmitter.java:copyAndConfigureFiles(153)) - Hadoop command-line option parsing not performed. Implement the Tool interface and execute your application with ToolRunner to remedy this.
2018-10-20 00:24:42,206 INFO  [main] input.FileInputFormat (FileInputFormat.java:listStatus(281)) - Total input paths to process : 1
2018-10-20 00:24:42,244 INFO  [main] mapreduce.JobSubmitter (JobSubmitter.java:submitJobInternal(494)) - number of splits:1
2018-10-20 00:24:42,407 INFO  [main] mapreduce.JobSubmitter (JobSubmitter.java:printTokens(583)) - Submitting tokens for job: job_local1075008924_0001
2018-10-20 00:24:42,808 INFO  [main] mapreduce.Job (Job.java:submit(1300)) - The url to track the job: http://localhost:8080/
2018-10-20 00:24:42,809 INFO  [main] mapreduce.Job (Job.java:monitorAndPrintJob(1345)) - Running job: job_local1075008924_0001
2018-10-20 00:24:42,813 INFO  [Thread-13] mapred.LocalJobRunner (LocalJobRunner.java:createOutputCommitter(471)) - OutputCommitter set in config null
2018-10-20 00:24:42,829 INFO  [Thread-13] mapred.LocalJobRunner (LocalJobRunner.java:createOutputCommitter(489)) - OutputCommitter is org.apache.hadoop.mapreduce.lib.output.FileOutputCommitter
2018-10-20 00:24:42,956 INFO  [Thread-13] mapred.LocalJobRunner (LocalJobRunner.java:runTasks(448)) - Waiting for map tasks
2018-10-20 00:24:42,957 INFO  [LocalJobRunner Map Task Executor #0] mapred.LocalJobRunner (LocalJobRunner.java:run(224)) - Starting task: attempt_local1075008924_0001_m_000000_0
2018-10-20 00:24:43,000 INFO  [LocalJobRunner Map Task Executor #0] mapred.Task (Task.java:initialize(587)) -  Using ResourceCalculatorProcessTree : [ ]
2018-10-20 00:24:43,003 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:runNewMapper(753)) - Processing split: file:/home/ptrivedi/project3/small-graph.txt:0+3541
2018-10-20 00:24:43,182 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:setEquator(1202)) - (EQUATOR) 0 kvi 26214396(104857584)
2018-10-20 00:24:43,183 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:init(995)) - mapreduce.task.io.sort.mb: 100
2018-10-20 00:24:43,183 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:init(996)) - soft limit at 83886080
2018-10-20 00:24:43,183 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:init(997)) - bufstart = 0; bufvoid = 104857600
2018-10-20 00:24:43,184 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:init(998)) - kvstart = 26214396; length = 6553600
2018-10-20 00:24:43,198 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:createSortingCollector(402)) - Map output collector class = org.apache.hadoop.mapred.MapTask$MapOutputBuffer
java.lang.NullPointerException
java.lang.NullPointerException
java.lang.NullPointerException
java.lang.NullPointerException
java.lang.NullPointerException
java.lang.NullPointerException
java.lang.NullPointerException
java.lang.NullPointerException
java.lang.NullPointerException
java.lang.NullPointerException
java.lang.NullPointerException
java.lang.NullPointerException
java.lang.NullPointerException
java.lang.NullPointerException
java.lang.NullPointerException
java.lang.NullPointerException
java.lang.NullPointerException
java.lang.NullPointerException
java.lang.NullPointerException
java.lang.NullPointerException
java.lang.NullPointerException
java.lang.NullPointerException
java.lang.NullPointerException
java.lang.NullPointerException
java.lang.NullPointerException
java.lang.NullPointerException
java.lang.NullPointerException
java.lang.NullPointerException
java.lang.NullPointerException
java.lang.NullPointerException
java.lang.NullPointerException
java.lang.NullPointerException
java.lang.NullPointerException
java.lang.NullPointerException
java.lang.NullPointerException
java.lang.NullPointerException
java.lang.NullPointerException
java.lang.NullPointerException
java.lang.NullPointerException
java.lang.NullPointerException
java.lang.NullPointerException
java.lang.NullPointerException
java.lang.NullPointerException
java.lang.NullPointerException
java.lang.NullPointerException
java.lang.NullPointerException
java.lang.NullPointerException
java.lang.NullPointerException
java.lang.NullPointerException
java.lang.NullPointerException
java.lang.NullPointerException
java.lang.NullPointerException
java.lang.NullPointerException
java.lang.NullPointerException
java.lang.NullPointerException
java.lang.NullPointerException
java.lang.NullPointerException
java.lang.NullPointerException
java.lang.NullPointerException
java.lang.NullPointerException
java.lang.NullPointerException
java.lang.NullPointerException
java.lang.NullPointerException
java.lang.NullPointerException
2018-10-20 00:24:43,237 INFO  [LocalJobRunner Map Task Executor #0] mapred.LocalJobRunner (LocalJobRunner.java:statusUpdate(591)) - 
2018-10-20 00:24:43,237 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:flush(1457)) - Starting flush of map output
2018-10-20 00:24:43,237 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:flush(1475)) - Spilling map output
2018-10-20 00:24:43,237 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:flush(1476)) - bufstart = 0; bufend = 1664; bufvoid = 104857600
2018-10-20 00:24:43,237 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:flush(1478)) - kvstart = 26214396(104857584); kvend = 26214144(104856576); length = 253/6553600
2018-10-20 00:24:43,244 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:sortAndSpill(1660)) - Finished spill 0
2018-10-20 00:24:43,251 INFO  [LocalJobRunner Map Task Executor #0] mapred.Task (Task.java:done(1001)) - Task:attempt_local1075008924_0001_m_000000_0 is done. And is in the process of committing
2018-10-20 00:24:43,263 INFO  [LocalJobRunner Map Task Executor #0] mapred.LocalJobRunner (LocalJobRunner.java:statusUpdate(591)) - map
2018-10-20 00:24:43,263 INFO  [LocalJobRunner Map Task Executor #0] mapred.Task (Task.java:sendDone(1121)) - Task 'attempt_local1075008924_0001_m_000000_0' done.
2018-10-20 00:24:43,264 INFO  [LocalJobRunner Map Task Executor #0] mapred.LocalJobRunner (LocalJobRunner.java:run(249)) - Finishing task: attempt_local1075008924_0001_m_000000_0
2018-10-20 00:24:43,264 INFO  [Thread-13] mapred.LocalJobRunner (LocalJobRunner.java:runTasks(456)) - map task executor complete.
2018-10-20 00:24:43,269 INFO  [Thread-13] mapred.LocalJobRunner (LocalJobRunner.java:runTasks(448)) - Waiting for reduce tasks
2018-10-20 00:24:43,270 INFO  [pool-3-thread-1] mapred.LocalJobRunner (LocalJobRunner.java:run(302)) - Starting task: attempt_local1075008924_0001_r_000000_0
2018-10-20 00:24:43,275 INFO  [pool-3-thread-1] mapred.Task (Task.java:initialize(587)) -  Using ResourceCalculatorProcessTree : [ ]
2018-10-20 00:24:43,277 INFO  [pool-3-thread-1] mapred.ReduceTask (ReduceTask.java:run(362)) - Using ShuffleConsumerPlugin: org.apache.hadoop.mapreduce.task.reduce.Shuffle@4f92a450
2018-10-20 00:24:43,290 INFO  [pool-3-thread-1] reduce.MergeManagerImpl (MergeManagerImpl.java:<init>(196)) - MergerManager: memoryLimit=703542080, maxSingleShuffleLimit=175885520, mergeThreshold=464337792, ioSortFactor=10, memToMemMergeOutputsThreshold=10
2018-10-20 00:24:43,305 INFO  [EventFetcher for fetching Map Completion Events] reduce.EventFetcher (EventFetcher.java:run(61)) - attempt_local1075008924_0001_r_000000_0 Thread started: EventFetcher for fetching Map Completion Events
2018-10-20 00:24:43,379 INFO  [localfetcher#1] reduce.LocalFetcher (LocalFetcher.java:copyMapOutput(141)) - localfetcher#1 about to shuffle output of map attempt_local1075008924_0001_m_000000_0 decomp: 1794 len: 1798 to MEMORY
2018-10-20 00:24:43,395 INFO  [localfetcher#1] reduce.InMemoryMapOutput (InMemoryMapOutput.java:shuffle(100)) - Read 1794 bytes from map-output for attempt_local1075008924_0001_m_000000_0
2018-10-20 00:24:43,433 INFO  [localfetcher#1] reduce.MergeManagerImpl (MergeManagerImpl.java:closeInMemoryFile(314)) - closeInMemoryFile -> map-output of size: 1794, inMemoryMapOutputs.size() -> 1, commitMemory -> 0, usedMemory ->1794
2018-10-20 00:24:43,434 INFO  [EventFetcher for fetching Map Completion Events] reduce.EventFetcher (EventFetcher.java:run(76)) - EventFetcher is interrupted.. Returning
2018-10-20 00:24:43,434 INFO  [pool-3-thread-1] mapred.LocalJobRunner (LocalJobRunner.java:statusUpdate(591)) - 1 / 1 copied.
2018-10-20 00:24:43,434 INFO  [pool-3-thread-1] reduce.MergeManagerImpl (MergeManagerImpl.java:finalMerge(674)) - finalMerge called with 1 in-memory map-outputs and 0 on-disk map-outputs
2018-10-20 00:24:43,439 INFO  [pool-3-thread-1] mapred.Merger (Merger.java:merge(597)) - Merging 1 sorted segments
2018-10-20 00:24:43,449 INFO  [pool-3-thread-1] mapred.Merger (Merger.java:merge(696)) - Down to the last merge-pass, with 1 segments left of total size: 1784 bytes
2018-10-20 00:24:43,450 INFO  [pool-3-thread-1] reduce.MergeManagerImpl (MergeManagerImpl.java:finalMerge(751)) - Merged 1 segments, 1794 bytes to disk to satisfy reduce memory limit
2018-10-20 00:24:43,451 INFO  [pool-3-thread-1] reduce.MergeManagerImpl (MergeManagerImpl.java:finalMerge(781)) - Merging 1 files, 1798 bytes from disk
2018-10-20 00:24:43,451 INFO  [pool-3-thread-1] reduce.MergeManagerImpl (MergeManagerImpl.java:finalMerge(796)) - Merging 0 segments, 0 bytes from memory into reduce
2018-10-20 00:24:43,451 INFO  [pool-3-thread-1] mapred.Merger (Merger.java:merge(597)) - Merging 1 sorted segments
2018-10-20 00:24:43,452 INFO  [pool-3-thread-1] mapred.Merger (Merger.java:merge(696)) - Down to the last merge-pass, with 1 segments left of total size: 1784 bytes
2018-10-20 00:24:43,452 INFO  [pool-3-thread-1] mapred.LocalJobRunner (LocalJobRunner.java:statusUpdate(591)) - 1 / 1 copied.
2018-10-20 00:24:43,498 INFO  [pool-3-thread-1] Configuration.deprecation (Configuration.java:warnOnceIfDeprecated(1049)) - mapred.skip.on is deprecated. Instead, use mapreduce.job.skiprecords
2018-10-20 00:24:43,504 INFO  [Thread-13] mapred.LocalJobRunner (LocalJobRunner.java:runTasks(456)) - reduce task executor complete.
2018-10-20 00:24:43,513 WARN  [Thread-13] mapred.LocalJobRunner (LocalJobRunner.java:run(560)) - job_local1075008924_0001
java.lang.Exception: java.io.EOFException
	at org.apache.hadoop.mapred.LocalJobRunner$Job.runTasks(LocalJobRunner.java:462)
	at org.apache.hadoop.mapred.LocalJobRunner$Job.run(LocalJobRunner.java:529)
Caused by: java.io.EOFException
	at java.io.DataInputStream.readFully(DataInputStream.java:197)
	at java.io.DataInputStream.readLong(DataInputStream.java:416)
	at Vertex.readFields(GraphPartition.java:104)
	at org.apache.hadoop.io.serializer.WritableSerialization$WritableDeserializer.deserialize(WritableSerialization.java:71)
	at org.apache.hadoop.io.serializer.WritableSerialization$WritableDeserializer.deserialize(WritableSerialization.java:42)
	at org.apache.hadoop.mapreduce.task.ReduceContextImpl.nextKeyValue(ReduceContextImpl.java:146)
	at org.apache.hadoop.mapreduce.task.ReduceContextImpl.nextKey(ReduceContextImpl.java:121)
	at org.apache.hadoop.mapreduce.lib.reduce.WrappedReducer$Context.nextKey(WrappedReducer.java:302)
	at org.apache.hadoop.mapreduce.Reducer.run(Reducer.java:170)
	at org.apache.hadoop.mapred.ReduceTask.runNewReducer(ReduceTask.java:627)
	at org.apache.hadoop.mapred.ReduceTask.run(ReduceTask.java:389)
	at org.apache.hadoop.mapred.LocalJobRunner$Job$ReduceTaskRunnable.run(LocalJobRunner.java:319)
	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:511)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1142)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:617)
	at java.lang.Thread.run(Thread.java:745)
2018-10-20 00:24:43,811 INFO  [main] mapreduce.Job (Job.java:monitorAndPrintJob(1366)) - Job job_local1075008924_0001 running in uber mode : false
2018-10-20 00:24:43,812 INFO  [main] mapreduce.Job (Job.java:monitorAndPrintJob(1373)) -  map 100% reduce 0%
2018-10-20 00:24:43,813 INFO  [main] mapreduce.Job (Job.java:monitorAndPrintJob(1386)) - Job job_local1075008924_0001 failed with state FAILED due to: NA
2018-10-20 00:24:43,821 INFO  [main] mapreduce.Job (Job.java:monitorAndPrintJob(1391)) - Counters: 33
	File System Counters
		FILE: Number of bytes read=11997
		FILE: Number of bytes written=264722
		FILE: Number of read operations=0
		FILE: Number of large read operations=0
		FILE: Number of write operations=0
	Map-Reduce Framework
		Map input records=64
		Map output records=64
		Map output bytes=1664
		Map output materialized bytes=1798
		Input split bytes=109
		Combine input records=0
		Combine output records=0
		Reduce input groups=0
		Reduce shuffle bytes=1798
		Reduce input records=0
		Reduce output records=0
		Spilled Records=64
		Shuffled Maps =1
		Failed Shuffles=0
		Merged Map outputs=1
		GC time elapsed (ms)=105
		CPU time spent (ms)=0
		Physical memory (bytes) snapshot=0
		Virtual memory (bytes) snapshot=0
		Total committed heap usage (bytes)=1005060096
	Shuffle Errors
		BAD_ID=0
		CONNECTION=0
		IO_ERROR=0
		WRONG_LENGTH=0
		WRONG_MAP=0
		WRONG_REDUCE=0
	File Input Format Counters 
		Bytes Read=3541
	File Output Format Counters 
		Bytes Written=0
2018-10-20 00:24:43,844 INFO  [main] jvm.JvmMetrics (JvmMetrics.java:init(71)) - Cannot initialize JVM Metrics with processName=JobTracker, sessionId= - already initialized
2018-10-20 00:24:43,856 WARN  [main] mapreduce.JobSubmitter (JobSubmitter.java:copyAndConfigureFiles(153)) - Hadoop command-line option parsing not performed. Implement the Tool interface and execute your application with ToolRunner to remedy this.
2018-10-20 00:24:43,874 INFO  [main] input.FileInputFormat (FileInputFormat.java:listStatus(281)) - Total input paths to process : 0
2018-10-20 00:24:43,886 INFO  [main] mapreduce.JobSubmitter (JobSubmitter.java:submitJobInternal(494)) - number of splits:0
2018-10-20 00:24:43,906 INFO  [main] mapreduce.JobSubmitter (JobSubmitter.java:printTokens(583)) - Submitting tokens for job: job_local501589511_0002
2018-10-20 00:24:44,056 INFO  [main] mapreduce.Job (Job.java:submit(1300)) - The url to track the job: http://localhost:8080/
2018-10-20 00:24:44,056 INFO  [main] mapreduce.Job (Job.java:monitorAndPrintJob(1345)) - Running job: job_local501589511_0002
2018-10-20 00:24:44,057 INFO  [Thread-34] mapred.LocalJobRunner (LocalJobRunner.java:createOutputCommitter(471)) - OutputCommitter set in config null
2018-10-20 00:24:44,058 INFO  [Thread-34] mapred.LocalJobRunner (LocalJobRunner.java:createOutputCommitter(489)) - OutputCommitter is org.apache.hadoop.mapreduce.lib.output.FileOutputCommitter
2018-10-20 00:24:44,070 INFO  [Thread-34] mapred.LocalJobRunner (LocalJobRunner.java:runTasks(448)) - Waiting for map tasks
2018-10-20 00:24:44,070 INFO  [Thread-34] mapred.LocalJobRunner (LocalJobRunner.java:runTasks(456)) - map task executor complete.
2018-10-20 00:24:44,083 INFO  [Thread-34] mapred.LocalJobRunner (LocalJobRunner.java:runTasks(448)) - Waiting for reduce tasks
2018-10-20 00:24:44,083 INFO  [pool-6-thread-1] mapred.LocalJobRunner (LocalJobRunner.java:run(302)) - Starting task: attempt_local501589511_0002_r_000000_0
2018-10-20 00:24:44,095 INFO  [pool-6-thread-1] mapred.Task (Task.java:initialize(587)) -  Using ResourceCalculatorProcessTree : [ ]
2018-10-20 00:24:44,095 INFO  [pool-6-thread-1] mapred.ReduceTask (ReduceTask.java:run(362)) - Using ShuffleConsumerPlugin: org.apache.hadoop.mapreduce.task.reduce.Shuffle@5e78e40e
2018-10-20 00:24:44,110 INFO  [pool-6-thread-1] reduce.MergeManagerImpl (MergeManagerImpl.java:<init>(196)) - MergerManager: memoryLimit=703542080, maxSingleShuffleLimit=175885520, mergeThreshold=464337792, ioSortFactor=10, memToMemMergeOutputsThreshold=10
2018-10-20 00:24:44,123 INFO  [EventFetcher for fetching Map Completion Events] reduce.EventFetcher (EventFetcher.java:run(61)) - attempt_local501589511_0002_r_000000_0 Thread started: EventFetcher for fetching Map Completion Events
2018-10-20 00:24:44,134 INFO  [EventFetcher for fetching Map Completion Events] reduce.EventFetcher (EventFetcher.java:run(76)) - EventFetcher is interrupted.. Returning
2018-10-20 00:24:44,135 INFO  [pool-6-thread-1] mapred.LocalJobRunner (LocalJobRunner.java:statusUpdate(591)) - 
2018-10-20 00:24:44,135 INFO  [pool-6-thread-1] reduce.MergeManagerImpl (MergeManagerImpl.java:finalMerge(674)) - finalMerge called with 0 in-memory map-outputs and 0 on-disk map-outputs
2018-10-20 00:24:44,135 INFO  [pool-6-thread-1] reduce.MergeManagerImpl (MergeManagerImpl.java:finalMerge(781)) - Merging 0 files, 0 bytes from disk
2018-10-20 00:24:44,135 INFO  [pool-6-thread-1] reduce.MergeManagerImpl (MergeManagerImpl.java:finalMerge(796)) - Merging 0 segments, 0 bytes from memory into reduce
2018-10-20 00:24:44,135 INFO  [pool-6-thread-1] mapred.Merger (Merger.java:merge(597)) - Merging 0 sorted segments
2018-10-20 00:24:44,136 INFO  [pool-6-thread-1] mapred.Merger (Merger.java:merge(696)) - Down to the last merge-pass, with 0 segments left of total size: 0 bytes
2018-10-20 00:24:44,136 INFO  [pool-6-thread-1] mapred.LocalJobRunner (LocalJobRunner.java:statusUpdate(591)) - 
2018-10-20 00:24:44,180 INFO  [pool-6-thread-1] mapred.Task (Task.java:done(1001)) - Task:attempt_local501589511_0002_r_000000_0 is done. And is in the process of committing
2018-10-20 00:24:44,181 INFO  [pool-6-thread-1] mapred.LocalJobRunner (LocalJobRunner.java:statusUpdate(591)) - 
2018-10-20 00:24:44,181 INFO  [pool-6-thread-1] mapred.Task (Task.java:commit(1162)) - Task attempt_local501589511_0002_r_000000_0 is allowed to commit now
2018-10-20 00:24:44,185 INFO  [pool-6-thread-1] output.FileOutputCommitter (FileOutputCommitter.java:commitTask(439)) - Saved output of task 'attempt_local501589511_0002_r_000000_0' to file:/home/ptrivedi/project3/intermediate/i1/_temporary/0/task_local501589511_0002_r_000000
2018-10-20 00:24:44,186 INFO  [pool-6-thread-1] mapred.LocalJobRunner (LocalJobRunner.java:statusUpdate(591)) - reduce > reduce
2018-10-20 00:24:44,186 INFO  [pool-6-thread-1] mapred.Task (Task.java:sendDone(1121)) - Task 'attempt_local501589511_0002_r_000000_0' done.
2018-10-20 00:24:44,186 INFO  [pool-6-thread-1] mapred.LocalJobRunner (LocalJobRunner.java:run(325)) - Finishing task: attempt_local501589511_0002_r_000000_0
2018-10-20 00:24:44,186 INFO  [Thread-34] mapred.LocalJobRunner (LocalJobRunner.java:runTasks(456)) - reduce task executor complete.
2018-10-20 00:24:45,057 INFO  [main] mapreduce.Job (Job.java:monitorAndPrintJob(1366)) - Job job_local501589511_0002 running in uber mode : false
2018-10-20 00:24:45,057 INFO  [main] mapreduce.Job (Job.java:monitorAndPrintJob(1373)) -  map 0% reduce 100%
2018-10-20 00:24:45,057 INFO  [main] mapreduce.Job (Job.java:monitorAndPrintJob(1384)) - Job job_local501589511_0002 completed successfully
2018-10-20 00:24:45,059 INFO  [main] mapreduce.Job (Job.java:monitorAndPrintJob(1391)) - Counters: 27
	File System Counters
		FILE: Number of bytes read=23938
		FILE: Number of bytes written=529756
		FILE: Number of read operations=0
		FILE: Number of large read operations=0
		FILE: Number of write operations=0
	Map-Reduce Framework
		Combine input records=0
		Combine output records=0
		Reduce input groups=0
		Reduce shuffle bytes=0
		Reduce input records=0
		Reduce output records=0
		Spilled Records=0
		Shuffled Maps =0
		Failed Shuffles=0
		Merged Map outputs=0
		GC time elapsed (ms)=0
		CPU time spent (ms)=0
		Physical memory (bytes) snapshot=0
		Virtual memory (bytes) snapshot=0
		Total committed heap usage (bytes)=1005060096
	Shuffle Errors
		BAD_ID=0
		CONNECTION=0
		IO_ERROR=0
		WRONG_LENGTH=0
		WRONG_MAP=0
		WRONG_REDUCE=0
	File Output Format Counters 
		Bytes Written=79
2018-10-20 00:24:45,075 INFO  [main] jvm.JvmMetrics (JvmMetrics.java:init(71)) - Cannot initialize JVM Metrics with processName=JobTracker, sessionId= - already initialized
2018-10-20 00:24:45,162 WARN  [main] mapreduce.JobSubmitter (JobSubmitter.java:copyAndConfigureFiles(153)) - Hadoop command-line option parsing not performed. Implement the Tool interface and execute your application with ToolRunner to remedy this.
2018-10-20 00:24:45,333 INFO  [main] input.FileInputFormat (FileInputFormat.java:listStatus(281)) - Total input paths to process : 1
2018-10-20 00:24:45,424 INFO  [main] mapreduce.JobSubmitter (JobSubmitter.java:submitJobInternal(494)) - number of splits:1
2018-10-20 00:24:45,487 INFO  [main] mapreduce.JobSubmitter (JobSubmitter.java:printTokens(583)) - Submitting tokens for job: job_local1245733052_0003
2018-10-20 00:24:45,679 INFO  [main] mapreduce.Job (Job.java:submit(1300)) - The url to track the job: http://localhost:8080/
2018-10-20 00:24:45,679 INFO  [main] mapreduce.Job (Job.java:monitorAndPrintJob(1345)) - Running job: job_local1245733052_0003
2018-10-20 00:24:45,680 INFO  [Thread-55] mapred.LocalJobRunner (LocalJobRunner.java:createOutputCommitter(471)) - OutputCommitter set in config null
2018-10-20 00:24:45,680 INFO  [Thread-55] mapred.LocalJobRunner (LocalJobRunner.java:createOutputCommitter(489)) - OutputCommitter is org.apache.hadoop.mapreduce.lib.output.FileOutputCommitter
2018-10-20 00:24:45,706 INFO  [Thread-55] mapred.LocalJobRunner (LocalJobRunner.java:runTasks(448)) - Waiting for map tasks
2018-10-20 00:24:45,707 INFO  [LocalJobRunner Map Task Executor #0] mapred.LocalJobRunner (LocalJobRunner.java:run(224)) - Starting task: attempt_local1245733052_0003_m_000000_0
2018-10-20 00:24:45,730 INFO  [LocalJobRunner Map Task Executor #0] mapred.Task (Task.java:initialize(587)) -  Using ResourceCalculatorProcessTree : [ ]
2018-10-20 00:24:45,731 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:runNewMapper(753)) - Processing split: file:/home/ptrivedi/project3/intermediate/i1/part-r-00000:0+67
2018-10-20 00:24:45,867 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:setEquator(1202)) - (EQUATOR) 0 kvi 26214396(104857584)
2018-10-20 00:24:45,867 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:init(995)) - mapreduce.task.io.sort.mb: 100
2018-10-20 00:24:45,868 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:init(996)) - soft limit at 83886080
2018-10-20 00:24:45,868 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:init(997)) - bufstart = 0; bufvoid = 104857600
2018-10-20 00:24:45,868 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:init(998)) - kvstart = 26214396; length = 6553600
2018-10-20 00:24:45,880 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:createSortingCollector(402)) - Map output collector class = org.apache.hadoop.mapred.MapTask$MapOutputBuffer
2018-10-20 00:24:45,890 INFO  [LocalJobRunner Map Task Executor #0] mapred.LocalJobRunner (LocalJobRunner.java:statusUpdate(591)) - 
2018-10-20 00:24:45,898 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:flush(1457)) - Starting flush of map output
2018-10-20 00:24:45,900 INFO  [LocalJobRunner Map Task Executor #0] mapred.Task (Task.java:done(1001)) - Task:attempt_local1245733052_0003_m_000000_0 is done. And is in the process of committing
2018-10-20 00:24:45,905 INFO  [LocalJobRunner Map Task Executor #0] mapred.LocalJobRunner (LocalJobRunner.java:statusUpdate(591)) - map
2018-10-20 00:24:45,905 INFO  [LocalJobRunner Map Task Executor #0] mapred.Task (Task.java:sendDone(1121)) - Task 'attempt_local1245733052_0003_m_000000_0' done.
2018-10-20 00:24:45,905 INFO  [LocalJobRunner Map Task Executor #0] mapred.LocalJobRunner (LocalJobRunner.java:run(249)) - Finishing task: attempt_local1245733052_0003_m_000000_0
2018-10-20 00:24:45,905 INFO  [Thread-55] mapred.LocalJobRunner (LocalJobRunner.java:runTasks(456)) - map task executor complete.
2018-10-20 00:24:45,914 INFO  [Thread-55] mapred.LocalJobRunner (LocalJobRunner.java:runTasks(448)) - Waiting for reduce tasks
2018-10-20 00:24:45,921 INFO  [pool-9-thread-1] mapred.LocalJobRunner (LocalJobRunner.java:run(302)) - Starting task: attempt_local1245733052_0003_r_000000_0
2018-10-20 00:24:45,933 INFO  [pool-9-thread-1] mapred.Task (Task.java:initialize(587)) -  Using ResourceCalculatorProcessTree : [ ]
2018-10-20 00:24:45,934 INFO  [pool-9-thread-1] mapred.ReduceTask (ReduceTask.java:run(362)) - Using ShuffleConsumerPlugin: org.apache.hadoop.mapreduce.task.reduce.Shuffle@248b0ebb
2018-10-20 00:24:45,938 INFO  [pool-9-thread-1] reduce.MergeManagerImpl (MergeManagerImpl.java:<init>(196)) - MergerManager: memoryLimit=703542080, maxSingleShuffleLimit=175885520, mergeThreshold=464337792, ioSortFactor=10, memToMemMergeOutputsThreshold=10
2018-10-20 00:24:45,942 INFO  [EventFetcher for fetching Map Completion Events] reduce.EventFetcher (EventFetcher.java:run(61)) - attempt_local1245733052_0003_r_000000_0 Thread started: EventFetcher for fetching Map Completion Events
2018-10-20 00:24:45,946 INFO  [localfetcher#3] reduce.LocalFetcher (LocalFetcher.java:copyMapOutput(141)) - localfetcher#3 about to shuffle output of map attempt_local1245733052_0003_m_000000_0 decomp: 2 len: 6 to MEMORY
2018-10-20 00:24:45,947 INFO  [localfetcher#3] reduce.InMemoryMapOutput (InMemoryMapOutput.java:shuffle(100)) - Read 2 bytes from map-output for attempt_local1245733052_0003_m_000000_0
2018-10-20 00:24:45,947 INFO  [localfetcher#3] reduce.MergeManagerImpl (MergeManagerImpl.java:closeInMemoryFile(314)) - closeInMemoryFile -> map-output of size: 2, inMemoryMapOutputs.size() -> 1, commitMemory -> 0, usedMemory ->2
2018-10-20 00:24:45,947 INFO  [EventFetcher for fetching Map Completion Events] reduce.EventFetcher (EventFetcher.java:run(76)) - EventFetcher is interrupted.. Returning
2018-10-20 00:24:45,948 INFO  [pool-9-thread-1] mapred.LocalJobRunner (LocalJobRunner.java:statusUpdate(591)) - 1 / 1 copied.
2018-10-20 00:24:45,948 INFO  [pool-9-thread-1] reduce.MergeManagerImpl (MergeManagerImpl.java:finalMerge(674)) - finalMerge called with 1 in-memory map-outputs and 0 on-disk map-outputs
2018-10-20 00:24:45,948 INFO  [pool-9-thread-1] mapred.Merger (Merger.java:merge(597)) - Merging 1 sorted segments
2018-10-20 00:24:45,954 INFO  [pool-9-thread-1] mapred.Merger (Merger.java:merge(696)) - Down to the last merge-pass, with 0 segments left of total size: 0 bytes
2018-10-20 00:24:45,954 INFO  [pool-9-thread-1] reduce.MergeManagerImpl (MergeManagerImpl.java:finalMerge(751)) - Merged 1 segments, 2 bytes to disk to satisfy reduce memory limit
2018-10-20 00:24:45,954 INFO  [pool-9-thread-1] reduce.MergeManagerImpl (MergeManagerImpl.java:finalMerge(781)) - Merging 1 files, 6 bytes from disk
2018-10-20 00:24:45,955 INFO  [pool-9-thread-1] reduce.MergeManagerImpl (MergeManagerImpl.java:finalMerge(796)) - Merging 0 segments, 0 bytes from memory into reduce
2018-10-20 00:24:45,955 INFO  [pool-9-thread-1] mapred.Merger (Merger.java:merge(597)) - Merging 1 sorted segments
2018-10-20 00:24:45,955 INFO  [pool-9-thread-1] mapred.Merger (Merger.java:merge(696)) - Down to the last merge-pass, with 0 segments left of total size: 0 bytes
2018-10-20 00:24:45,955 INFO  [pool-9-thread-1] mapred.LocalJobRunner (LocalJobRunner.java:statusUpdate(591)) - 1 / 1 copied.
2018-10-20 00:24:45,974 INFO  [pool-9-thread-1] mapred.Task (Task.java:done(1001)) - Task:attempt_local1245733052_0003_r_000000_0 is done. And is in the process of committing
2018-10-20 00:24:45,974 INFO  [pool-9-thread-1] mapred.LocalJobRunner (LocalJobRunner.java:statusUpdate(591)) - 1 / 1 copied.
2018-10-20 00:24:45,974 INFO  [pool-9-thread-1] mapred.Task (Task.java:commit(1162)) - Task attempt_local1245733052_0003_r_000000_0 is allowed to commit now
2018-10-20 00:24:45,978 INFO  [pool-9-thread-1] output.FileOutputCommitter (FileOutputCommitter.java:commitTask(439)) - Saved output of task 'attempt_local1245733052_0003_r_000000_0' to file:/home/ptrivedi/project3/intermediate/i2/_temporary/0/task_local1245733052_0003_r_000000
2018-10-20 00:24:45,978 INFO  [pool-9-thread-1] mapred.LocalJobRunner (LocalJobRunner.java:statusUpdate(591)) - reduce > reduce
2018-10-20 00:24:45,979 INFO  [pool-9-thread-1] mapred.Task (Task.java:sendDone(1121)) - Task 'attempt_local1245733052_0003_r_000000_0' done.
2018-10-20 00:24:45,979 INFO  [pool-9-thread-1] mapred.LocalJobRunner (LocalJobRunner.java:run(325)) - Finishing task: attempt_local1245733052_0003_r_000000_0
2018-10-20 00:24:45,979 INFO  [Thread-55] mapred.LocalJobRunner (LocalJobRunner.java:runTasks(456)) - reduce task executor complete.
2018-10-20 00:24:46,679 INFO  [main] mapreduce.Job (Job.java:monitorAndPrintJob(1366)) - Job job_local1245733052_0003 running in uber mode : false
2018-10-20 00:24:46,680 INFO  [main] mapreduce.Job (Job.java:monitorAndPrintJob(1373)) -  map 100% reduce 100%
2018-10-20 00:24:46,680 INFO  [main] mapreduce.Job (Job.java:monitorAndPrintJob(1384)) - Job job_local1245733052_0003 completed successfully
2018-10-20 00:24:46,685 INFO  [main] mapreduce.Job (Job.java:monitorAndPrintJob(1391)) - Counters: 33
	File System Counters
		FILE: Number of bytes read=65012
		FILE: Number of bytes written=1588835
		FILE: Number of read operations=0
		FILE: Number of large read operations=0
		FILE: Number of write operations=0
	Map-Reduce Framework
		Map input records=0
		Map output records=0
		Map output bytes=0
		Map output materialized bytes=6
		Input split bytes=122
		Combine input records=0
		Combine output records=0
		Reduce input groups=0
		Reduce shuffle bytes=6
		Reduce input records=0
		Reduce output records=0
		Spilled Records=0
		Shuffled Maps =1
		Failed Shuffles=0
		Merged Map outputs=1
		GC time elapsed (ms)=107
		CPU time spent (ms)=0
		Physical memory (bytes) snapshot=0
		Virtual memory (bytes) snapshot=0
		Total committed heap usage (bytes)=2010120192
	Shuffle Errors
		BAD_ID=0
		CONNECTION=0
		IO_ERROR=0
		WRONG_LENGTH=0
		WRONG_MAP=0
		WRONG_REDUCE=0
	File Input Format Counters 
		Bytes Read=79
	File Output Format Counters 
		Bytes Written=79
2018-10-20 00:24:46,700 INFO  [main] jvm.JvmMetrics (JvmMetrics.java:init(71)) - Cannot initialize JVM Metrics with processName=JobTracker, sessionId= - already initialized
2018-10-20 00:24:46,716 WARN  [main] mapreduce.JobSubmitter (JobSubmitter.java:copyAndConfigureFiles(153)) - Hadoop command-line option parsing not performed. Implement the Tool interface and execute your application with ToolRunner to remedy this.
2018-10-20 00:24:46,775 INFO  [main] input.FileInputFormat (FileInputFormat.java:listStatus(281)) - Total input paths to process : 1
2018-10-20 00:24:46,787 INFO  [main] mapreduce.JobSubmitter (JobSubmitter.java:submitJobInternal(494)) - number of splits:1
2018-10-20 00:24:46,797 INFO  [main] mapreduce.JobSubmitter (JobSubmitter.java:printTokens(583)) - Submitting tokens for job: job_local1954296831_0004
2018-10-20 00:24:46,918 INFO  [main] mapreduce.Job (Job.java:submit(1300)) - The url to track the job: http://localhost:8080/
2018-10-20 00:24:46,918 INFO  [main] mapreduce.Job (Job.java:monitorAndPrintJob(1345)) - Running job: job_local1954296831_0004
2018-10-20 00:24:46,919 INFO  [Thread-77] mapred.LocalJobRunner (LocalJobRunner.java:createOutputCommitter(471)) - OutputCommitter set in config null
2018-10-20 00:24:46,919 INFO  [Thread-77] mapred.LocalJobRunner (LocalJobRunner.java:createOutputCommitter(489)) - OutputCommitter is org.apache.hadoop.mapreduce.lib.output.FileOutputCommitter
2018-10-20 00:24:46,943 INFO  [Thread-77] mapred.LocalJobRunner (LocalJobRunner.java:runTasks(448)) - Waiting for map tasks
2018-10-20 00:24:46,943 INFO  [LocalJobRunner Map Task Executor #0] mapred.LocalJobRunner (LocalJobRunner.java:run(224)) - Starting task: attempt_local1954296831_0004_m_000000_0
2018-10-20 00:24:46,955 INFO  [LocalJobRunner Map Task Executor #0] mapred.Task (Task.java:initialize(587)) -  Using ResourceCalculatorProcessTree : [ ]
2018-10-20 00:24:46,957 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:runNewMapper(753)) - Processing split: file:/home/ptrivedi/project3/intermediate/i2/part-r-00000:0+67
2018-10-20 00:24:47,060 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:setEquator(1202)) - (EQUATOR) 0 kvi 26214396(104857584)
2018-10-20 00:24:47,061 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:init(995)) - mapreduce.task.io.sort.mb: 100
2018-10-20 00:24:47,061 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:init(996)) - soft limit at 83886080
2018-10-20 00:24:47,061 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:init(997)) - bufstart = 0; bufvoid = 104857600
2018-10-20 00:24:47,061 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:init(998)) - kvstart = 26214396; length = 6553600
2018-10-20 00:24:47,065 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:createSortingCollector(402)) - Map output collector class = org.apache.hadoop.mapred.MapTask$MapOutputBuffer
2018-10-20 00:24:47,071 INFO  [LocalJobRunner Map Task Executor #0] mapred.LocalJobRunner (LocalJobRunner.java:statusUpdate(591)) - 
2018-10-20 00:24:47,071 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:flush(1457)) - Starting flush of map output
2018-10-20 00:24:47,073 INFO  [LocalJobRunner Map Task Executor #0] mapred.Task (Task.java:done(1001)) - Task:attempt_local1954296831_0004_m_000000_0 is done. And is in the process of committing
2018-10-20 00:24:47,087 INFO  [LocalJobRunner Map Task Executor #0] mapred.LocalJobRunner (LocalJobRunner.java:statusUpdate(591)) - map
2018-10-20 00:24:47,088 INFO  [LocalJobRunner Map Task Executor #0] mapred.Task (Task.java:sendDone(1121)) - Task 'attempt_local1954296831_0004_m_000000_0' done.
2018-10-20 00:24:47,088 INFO  [LocalJobRunner Map Task Executor #0] mapred.LocalJobRunner (LocalJobRunner.java:run(249)) - Finishing task: attempt_local1954296831_0004_m_000000_0
2018-10-20 00:24:47,090 INFO  [Thread-77] mapred.LocalJobRunner (LocalJobRunner.java:runTasks(456)) - map task executor complete.
2018-10-20 00:24:47,093 INFO  [Thread-77] mapred.LocalJobRunner (LocalJobRunner.java:runTasks(448)) - Waiting for reduce tasks
2018-10-20 00:24:47,100 INFO  [pool-12-thread-1] mapred.LocalJobRunner (LocalJobRunner.java:run(302)) - Starting task: attempt_local1954296831_0004_r_000000_0
2018-10-20 00:24:47,101 INFO  [pool-12-thread-1] mapred.Task (Task.java:initialize(587)) -  Using ResourceCalculatorProcessTree : [ ]
2018-10-20 00:24:47,101 INFO  [pool-12-thread-1] mapred.ReduceTask (ReduceTask.java:run(362)) - Using ShuffleConsumerPlugin: org.apache.hadoop.mapreduce.task.reduce.Shuffle@46d050ff
2018-10-20 00:24:47,106 INFO  [pool-12-thread-1] reduce.MergeManagerImpl (MergeManagerImpl.java:<init>(196)) - MergerManager: memoryLimit=703542080, maxSingleShuffleLimit=175885520, mergeThreshold=464337792, ioSortFactor=10, memToMemMergeOutputsThreshold=10
2018-10-20 00:24:47,108 INFO  [EventFetcher for fetching Map Completion Events] reduce.EventFetcher (EventFetcher.java:run(61)) - attempt_local1954296831_0004_r_000000_0 Thread started: EventFetcher for fetching Map Completion Events
2018-10-20 00:24:47,109 INFO  [localfetcher#4] reduce.LocalFetcher (LocalFetcher.java:copyMapOutput(141)) - localfetcher#4 about to shuffle output of map attempt_local1954296831_0004_m_000000_0 decomp: 2 len: 6 to MEMORY
2018-10-20 00:24:47,109 INFO  [localfetcher#4] reduce.InMemoryMapOutput (InMemoryMapOutput.java:shuffle(100)) - Read 2 bytes from map-output for attempt_local1954296831_0004_m_000000_0
2018-10-20 00:24:47,109 INFO  [localfetcher#4] reduce.MergeManagerImpl (MergeManagerImpl.java:closeInMemoryFile(314)) - closeInMemoryFile -> map-output of size: 2, inMemoryMapOutputs.size() -> 1, commitMemory -> 0, usedMemory ->2
2018-10-20 00:24:47,109 INFO  [EventFetcher for fetching Map Completion Events] reduce.EventFetcher (EventFetcher.java:run(76)) - EventFetcher is interrupted.. Returning
2018-10-20 00:24:47,110 INFO  [pool-12-thread-1] mapred.LocalJobRunner (LocalJobRunner.java:statusUpdate(591)) - 1 / 1 copied.
2018-10-20 00:24:47,110 INFO  [pool-12-thread-1] reduce.MergeManagerImpl (MergeManagerImpl.java:finalMerge(674)) - finalMerge called with 1 in-memory map-outputs and 0 on-disk map-outputs
2018-10-20 00:24:47,110 INFO  [pool-12-thread-1] mapred.Merger (Merger.java:merge(597)) - Merging 1 sorted segments
2018-10-20 00:24:47,112 INFO  [pool-12-thread-1] mapred.Merger (Merger.java:merge(696)) - Down to the last merge-pass, with 0 segments left of total size: 0 bytes
2018-10-20 00:24:47,112 INFO  [pool-12-thread-1] reduce.MergeManagerImpl (MergeManagerImpl.java:finalMerge(751)) - Merged 1 segments, 2 bytes to disk to satisfy reduce memory limit
2018-10-20 00:24:47,113 INFO  [pool-12-thread-1] reduce.MergeManagerImpl (MergeManagerImpl.java:finalMerge(781)) - Merging 1 files, 6 bytes from disk
2018-10-20 00:24:47,113 INFO  [pool-12-thread-1] reduce.MergeManagerImpl (MergeManagerImpl.java:finalMerge(796)) - Merging 0 segments, 0 bytes from memory into reduce
2018-10-20 00:24:47,113 INFO  [pool-12-thread-1] mapred.Merger (Merger.java:merge(597)) - Merging 1 sorted segments
2018-10-20 00:24:47,113 INFO  [pool-12-thread-1] mapred.Merger (Merger.java:merge(696)) - Down to the last merge-pass, with 0 segments left of total size: 0 bytes
2018-10-20 00:24:47,113 INFO  [pool-12-thread-1] mapred.LocalJobRunner (LocalJobRunner.java:statusUpdate(591)) - 1 / 1 copied.
2018-10-20 00:24:47,127 INFO  [pool-12-thread-1] mapred.Task (Task.java:done(1001)) - Task:attempt_local1954296831_0004_r_000000_0 is done. And is in the process of committing
2018-10-20 00:24:47,128 INFO  [pool-12-thread-1] mapred.LocalJobRunner (LocalJobRunner.java:statusUpdate(591)) - 1 / 1 copied.
2018-10-20 00:24:47,128 INFO  [pool-12-thread-1] mapred.Task (Task.java:commit(1162)) - Task attempt_local1954296831_0004_r_000000_0 is allowed to commit now
2018-10-20 00:24:47,137 INFO  [pool-12-thread-1] output.FileOutputCommitter (FileOutputCommitter.java:commitTask(439)) - Saved output of task 'attempt_local1954296831_0004_r_000000_0' to file:/home/ptrivedi/project3/intermediate/i3/_temporary/0/task_local1954296831_0004_r_000000
2018-10-20 00:24:47,137 INFO  [pool-12-thread-1] mapred.LocalJobRunner (LocalJobRunner.java:statusUpdate(591)) - reduce > reduce
2018-10-20 00:24:47,137 INFO  [pool-12-thread-1] mapred.Task (Task.java:sendDone(1121)) - Task 'attempt_local1954296831_0004_r_000000_0' done.
2018-10-20 00:24:47,137 INFO  [pool-12-thread-1] mapred.LocalJobRunner (LocalJobRunner.java:run(325)) - Finishing task: attempt_local1954296831_0004_r_000000_0
2018-10-20 00:24:47,138 INFO  [Thread-77] mapred.LocalJobRunner (LocalJobRunner.java:runTasks(456)) - reduce task executor complete.
2018-10-20 00:24:47,918 INFO  [main] mapreduce.Job (Job.java:monitorAndPrintJob(1366)) - Job job_local1954296831_0004 running in uber mode : false
2018-10-20 00:24:47,919 INFO  [main] mapreduce.Job (Job.java:monitorAndPrintJob(1373)) -  map 100% reduce 100%
2018-10-20 00:24:47,919 INFO  [main] mapreduce.Job (Job.java:monitorAndPrintJob(1384)) - Job job_local1954296831_0004 completed successfully
2018-10-20 00:24:47,923 INFO  [main] mapreduce.Job (Job.java:monitorAndPrintJob(1391)) - Counters: 33
	File System Counters
		FILE: Number of bytes read=82192
		FILE: Number of bytes written=2118243
		FILE: Number of read operations=0
		FILE: Number of large read operations=0
		FILE: Number of write operations=0
	Map-Reduce Framework
		Map input records=0
		Map output records=0
		Map output bytes=0
		Map output materialized bytes=6
		Input split bytes=122
		Combine input records=0
		Combine output records=0
		Reduce input groups=0
		Reduce shuffle bytes=6
		Reduce input records=0
		Reduce output records=0
		Spilled Records=0
		Shuffled Maps =1
		Failed Shuffles=0
		Merged Map outputs=1
		GC time elapsed (ms)=84
		CPU time spent (ms)=0
		Physical memory (bytes) snapshot=0
		Virtual memory (bytes) snapshot=0
		Total committed heap usage (bytes)=2010120192
	Shuffle Errors
		BAD_ID=0
		CONNECTION=0
		IO_ERROR=0
		WRONG_LENGTH=0
		WRONG_MAP=0
		WRONG_REDUCE=0
	File Input Format Counters 
		Bytes Read=79
	File Output Format Counters 
		Bytes Written=79
2018-10-20 00:24:47,934 INFO  [main] jvm.JvmMetrics (JvmMetrics.java:init(71)) - Cannot initialize JVM Metrics with processName=JobTracker, sessionId= - already initialized
2018-10-20 00:24:47,957 WARN  [main] mapreduce.JobSubmitter (JobSubmitter.java:copyAndConfigureFiles(153)) - Hadoop command-line option parsing not performed. Implement the Tool interface and execute your application with ToolRunner to remedy this.
2018-10-20 00:24:47,992 INFO  [main] input.FileInputFormat (FileInputFormat.java:listStatus(281)) - Total input paths to process : 1
2018-10-20 00:24:48,014 INFO  [main] mapreduce.JobSubmitter (JobSubmitter.java:submitJobInternal(494)) - number of splits:1
2018-10-20 00:24:48,026 INFO  [main] mapreduce.JobSubmitter (JobSubmitter.java:printTokens(583)) - Submitting tokens for job: job_local1276896946_0005
2018-10-20 00:24:48,134 INFO  [main] mapreduce.Job (Job.java:submit(1300)) - The url to track the job: http://localhost:8080/
2018-10-20 00:24:48,134 INFO  [main] mapreduce.Job (Job.java:monitorAndPrintJob(1345)) - Running job: job_local1276896946_0005
2018-10-20 00:24:48,135 INFO  [Thread-99] mapred.LocalJobRunner (LocalJobRunner.java:createOutputCommitter(471)) - OutputCommitter set in config null
2018-10-20 00:24:48,135 INFO  [Thread-99] mapred.LocalJobRunner (LocalJobRunner.java:createOutputCommitter(489)) - OutputCommitter is org.apache.hadoop.mapreduce.lib.output.FileOutputCommitter
2018-10-20 00:24:48,150 INFO  [Thread-99] mapred.LocalJobRunner (LocalJobRunner.java:runTasks(448)) - Waiting for map tasks
2018-10-20 00:24:48,150 INFO  [LocalJobRunner Map Task Executor #0] mapred.LocalJobRunner (LocalJobRunner.java:run(224)) - Starting task: attempt_local1276896946_0005_m_000000_0
2018-10-20 00:24:48,154 INFO  [LocalJobRunner Map Task Executor #0] mapred.Task (Task.java:initialize(587)) -  Using ResourceCalculatorProcessTree : [ ]
2018-10-20 00:24:48,155 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:runNewMapper(753)) - Processing split: file:/home/ptrivedi/project3/intermediate/i3/part-r-00000:0+67
2018-10-20 00:24:48,302 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:setEquator(1202)) - (EQUATOR) 0 kvi 26214396(104857584)
2018-10-20 00:24:48,302 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:init(995)) - mapreduce.task.io.sort.mb: 100
2018-10-20 00:24:48,302 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:init(996)) - soft limit at 83886080
2018-10-20 00:24:48,302 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:init(997)) - bufstart = 0; bufvoid = 104857600
2018-10-20 00:24:48,302 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:init(998)) - kvstart = 26214396; length = 6553600
2018-10-20 00:24:48,302 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:createSortingCollector(402)) - Map output collector class = org.apache.hadoop.mapred.MapTask$MapOutputBuffer
2018-10-20 00:24:48,307 INFO  [LocalJobRunner Map Task Executor #0] mapred.LocalJobRunner (LocalJobRunner.java:statusUpdate(591)) - 
2018-10-20 00:24:48,309 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:flush(1457)) - Starting flush of map output
2018-10-20 00:24:48,310 INFO  [LocalJobRunner Map Task Executor #0] mapred.Task (Task.java:done(1001)) - Task:attempt_local1276896946_0005_m_000000_0 is done. And is in the process of committing
2018-10-20 00:24:48,313 INFO  [LocalJobRunner Map Task Executor #0] mapred.LocalJobRunner (LocalJobRunner.java:statusUpdate(591)) - map
2018-10-20 00:24:48,313 INFO  [LocalJobRunner Map Task Executor #0] mapred.Task (Task.java:sendDone(1121)) - Task 'attempt_local1276896946_0005_m_000000_0' done.
2018-10-20 00:24:48,313 INFO  [LocalJobRunner Map Task Executor #0] mapred.LocalJobRunner (LocalJobRunner.java:run(249)) - Finishing task: attempt_local1276896946_0005_m_000000_0
2018-10-20 00:24:48,313 INFO  [Thread-99] mapred.LocalJobRunner (LocalJobRunner.java:runTasks(456)) - map task executor complete.
2018-10-20 00:24:48,314 INFO  [Thread-99] mapred.LocalJobRunner (LocalJobRunner.java:runTasks(448)) - Waiting for reduce tasks
2018-10-20 00:24:48,320 INFO  [pool-15-thread-1] mapred.LocalJobRunner (LocalJobRunner.java:run(302)) - Starting task: attempt_local1276896946_0005_r_000000_0
2018-10-20 00:24:48,324 INFO  [pool-15-thread-1] mapred.Task (Task.java:initialize(587)) -  Using ResourceCalculatorProcessTree : [ ]
2018-10-20 00:24:48,324 INFO  [pool-15-thread-1] mapred.ReduceTask (ReduceTask.java:run(362)) - Using ShuffleConsumerPlugin: org.apache.hadoop.mapreduce.task.reduce.Shuffle@189f0a03
2018-10-20 00:24:48,331 INFO  [pool-15-thread-1] reduce.MergeManagerImpl (MergeManagerImpl.java:<init>(196)) - MergerManager: memoryLimit=703542080, maxSingleShuffleLimit=175885520, mergeThreshold=464337792, ioSortFactor=10, memToMemMergeOutputsThreshold=10
2018-10-20 00:24:48,332 INFO  [EventFetcher for fetching Map Completion Events] reduce.EventFetcher (EventFetcher.java:run(61)) - attempt_local1276896946_0005_r_000000_0 Thread started: EventFetcher for fetching Map Completion Events
2018-10-20 00:24:48,333 INFO  [localfetcher#5] reduce.LocalFetcher (LocalFetcher.java:copyMapOutput(141)) - localfetcher#5 about to shuffle output of map attempt_local1276896946_0005_m_000000_0 decomp: 2 len: 6 to MEMORY
2018-10-20 00:24:48,333 INFO  [localfetcher#5] reduce.InMemoryMapOutput (InMemoryMapOutput.java:shuffle(100)) - Read 2 bytes from map-output for attempt_local1276896946_0005_m_000000_0
2018-10-20 00:24:48,334 INFO  [localfetcher#5] reduce.MergeManagerImpl (MergeManagerImpl.java:closeInMemoryFile(314)) - closeInMemoryFile -> map-output of size: 2, inMemoryMapOutputs.size() -> 1, commitMemory -> 0, usedMemory ->2
2018-10-20 00:24:48,334 INFO  [EventFetcher for fetching Map Completion Events] reduce.EventFetcher (EventFetcher.java:run(76)) - EventFetcher is interrupted.. Returning
2018-10-20 00:24:48,336 INFO  [pool-15-thread-1] mapred.LocalJobRunner (LocalJobRunner.java:statusUpdate(591)) - 1 / 1 copied.
2018-10-20 00:24:48,336 INFO  [pool-15-thread-1] reduce.MergeManagerImpl (MergeManagerImpl.java:finalMerge(674)) - finalMerge called with 1 in-memory map-outputs and 0 on-disk map-outputs
2018-10-20 00:24:48,337 INFO  [pool-15-thread-1] mapred.Merger (Merger.java:merge(597)) - Merging 1 sorted segments
2018-10-20 00:24:48,337 INFO  [pool-15-thread-1] mapred.Merger (Merger.java:merge(696)) - Down to the last merge-pass, with 0 segments left of total size: 0 bytes
2018-10-20 00:24:48,337 INFO  [pool-15-thread-1] reduce.MergeManagerImpl (MergeManagerImpl.java:finalMerge(751)) - Merged 1 segments, 2 bytes to disk to satisfy reduce memory limit
2018-10-20 00:24:48,337 INFO  [pool-15-thread-1] reduce.MergeManagerImpl (MergeManagerImpl.java:finalMerge(781)) - Merging 1 files, 6 bytes from disk
2018-10-20 00:24:48,337 INFO  [pool-15-thread-1] reduce.MergeManagerImpl (MergeManagerImpl.java:finalMerge(796)) - Merging 0 segments, 0 bytes from memory into reduce
2018-10-20 00:24:48,337 INFO  [pool-15-thread-1] mapred.Merger (Merger.java:merge(597)) - Merging 1 sorted segments
2018-10-20 00:24:48,338 INFO  [pool-15-thread-1] mapred.Merger (Merger.java:merge(696)) - Down to the last merge-pass, with 0 segments left of total size: 0 bytes
2018-10-20 00:24:48,338 INFO  [pool-15-thread-1] mapred.LocalJobRunner (LocalJobRunner.java:statusUpdate(591)) - 1 / 1 copied.
2018-10-20 00:24:48,355 INFO  [pool-15-thread-1] mapred.Task (Task.java:done(1001)) - Task:attempt_local1276896946_0005_r_000000_0 is done. And is in the process of committing
2018-10-20 00:24:48,355 INFO  [pool-15-thread-1] mapred.LocalJobRunner (LocalJobRunner.java:statusUpdate(591)) - 1 / 1 copied.
2018-10-20 00:24:48,356 INFO  [pool-15-thread-1] mapred.Task (Task.java:commit(1162)) - Task attempt_local1276896946_0005_r_000000_0 is allowed to commit now
2018-10-20 00:24:48,363 INFO  [pool-15-thread-1] output.FileOutputCommitter (FileOutputCommitter.java:commitTask(439)) - Saved output of task 'attempt_local1276896946_0005_r_000000_0' to file:/home/ptrivedi/project3/intermediate/i4/_temporary/0/task_local1276896946_0005_r_000000
2018-10-20 00:24:48,363 INFO  [pool-15-thread-1] mapred.LocalJobRunner (LocalJobRunner.java:statusUpdate(591)) - reduce > reduce
2018-10-20 00:24:48,363 INFO  [pool-15-thread-1] mapred.Task (Task.java:sendDone(1121)) - Task 'attempt_local1276896946_0005_r_000000_0' done.
2018-10-20 00:24:48,364 INFO  [pool-15-thread-1] mapred.LocalJobRunner (LocalJobRunner.java:run(325)) - Finishing task: attempt_local1276896946_0005_r_000000_0
2018-10-20 00:24:48,364 INFO  [Thread-99] mapred.LocalJobRunner (LocalJobRunner.java:runTasks(456)) - reduce task executor complete.
2018-10-20 00:24:49,134 INFO  [main] mapreduce.Job (Job.java:monitorAndPrintJob(1366)) - Job job_local1276896946_0005 running in uber mode : false
2018-10-20 00:24:49,135 INFO  [main] mapreduce.Job (Job.java:monitorAndPrintJob(1373)) -  map 100% reduce 100%
2018-10-20 00:24:49,135 INFO  [main] mapreduce.Job (Job.java:monitorAndPrintJob(1384)) - Job job_local1276896946_0005 completed successfully
2018-10-20 00:24:49,136 INFO  [main] mapreduce.Job (Job.java:monitorAndPrintJob(1391)) - Counters: 33
	File System Counters
		FILE: Number of bytes read=99372
		FILE: Number of bytes written=2647651
		FILE: Number of read operations=0
		FILE: Number of large read operations=0
		FILE: Number of write operations=0
	Map-Reduce Framework
		Map input records=0
		Map output records=0
		Map output bytes=0
		Map output materialized bytes=6
		Input split bytes=122
		Combine input records=0
		Combine output records=0
		Reduce input groups=0
		Reduce shuffle bytes=6
		Reduce input records=0
		Reduce output records=0
		Spilled Records=0
		Shuffled Maps =1
		Failed Shuffles=0
		Merged Map outputs=1
		GC time elapsed (ms)=128
		CPU time spent (ms)=0
		Physical memory (bytes) snapshot=0
		Virtual memory (bytes) snapshot=0
		Total committed heap usage (bytes)=2010120192
	Shuffle Errors
		BAD_ID=0
		CONNECTION=0
		IO_ERROR=0
		WRONG_LENGTH=0
		WRONG_MAP=0
		WRONG_REDUCE=0
	File Input Format Counters 
		Bytes Read=79
	File Output Format Counters 
		Bytes Written=79
2018-10-20 00:24:49,154 INFO  [main] jvm.JvmMetrics (JvmMetrics.java:init(71)) - Cannot initialize JVM Metrics with processName=JobTracker, sessionId= - already initialized
2018-10-20 00:24:49,165 WARN  [main] mapreduce.JobSubmitter (JobSubmitter.java:copyAndConfigureFiles(153)) - Hadoop command-line option parsing not performed. Implement the Tool interface and execute your application with ToolRunner to remedy this.
2018-10-20 00:24:49,192 INFO  [main] input.FileInputFormat (FileInputFormat.java:listStatus(281)) - Total input paths to process : 1
2018-10-20 00:24:49,200 INFO  [main] mapreduce.JobSubmitter (JobSubmitter.java:submitJobInternal(494)) - number of splits:1
2018-10-20 00:24:49,210 INFO  [main] mapreduce.JobSubmitter (JobSubmitter.java:printTokens(583)) - Submitting tokens for job: job_local286846883_0006
2018-10-20 00:24:49,285 INFO  [communication thread] mapred.LocalJobRunner (LocalJobRunner.java:statusUpdate(591)) - reduce > reduce
2018-10-20 00:24:49,336 INFO  [main] mapreduce.Job (Job.java:submit(1300)) - The url to track the job: http://localhost:8080/
2018-10-20 00:24:49,336 INFO  [main] mapreduce.Job (Job.java:monitorAndPrintJob(1345)) - Running job: job_local286846883_0006
2018-10-20 00:24:49,336 INFO  [Thread-121] mapred.LocalJobRunner (LocalJobRunner.java:createOutputCommitter(471)) - OutputCommitter set in config null
2018-10-20 00:24:49,337 INFO  [Thread-121] mapred.LocalJobRunner (LocalJobRunner.java:createOutputCommitter(489)) - OutputCommitter is org.apache.hadoop.mapreduce.lib.output.FileOutputCommitter
2018-10-20 00:24:49,362 INFO  [Thread-121] mapred.LocalJobRunner (LocalJobRunner.java:runTasks(448)) - Waiting for map tasks
2018-10-20 00:24:49,362 INFO  [LocalJobRunner Map Task Executor #0] mapred.LocalJobRunner (LocalJobRunner.java:run(224)) - Starting task: attempt_local286846883_0006_m_000000_0
2018-10-20 00:24:49,375 INFO  [LocalJobRunner Map Task Executor #0] mapred.Task (Task.java:initialize(587)) -  Using ResourceCalculatorProcessTree : [ ]
2018-10-20 00:24:49,376 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:runNewMapper(753)) - Processing split: file:/home/ptrivedi/project3/intermediate/i4/part-r-00000:0+67
2018-10-20 00:24:49,502 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:setEquator(1202)) - (EQUATOR) 0 kvi 26214396(104857584)
2018-10-20 00:24:49,502 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:init(995)) - mapreduce.task.io.sort.mb: 100
2018-10-20 00:24:49,502 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:init(996)) - soft limit at 83886080
2018-10-20 00:24:49,502 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:init(997)) - bufstart = 0; bufvoid = 104857600
2018-10-20 00:24:49,502 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:init(998)) - kvstart = 26214396; length = 6553600
2018-10-20 00:24:49,508 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:createSortingCollector(402)) - Map output collector class = org.apache.hadoop.mapred.MapTask$MapOutputBuffer
2018-10-20 00:24:49,510 INFO  [LocalJobRunner Map Task Executor #0] mapred.LocalJobRunner (LocalJobRunner.java:statusUpdate(591)) - 
2018-10-20 00:24:49,511 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:flush(1457)) - Starting flush of map output
2018-10-20 00:24:49,513 INFO  [LocalJobRunner Map Task Executor #0] mapred.Task (Task.java:done(1001)) - Task:attempt_local286846883_0006_m_000000_0 is done. And is in the process of committing
2018-10-20 00:24:49,515 INFO  [LocalJobRunner Map Task Executor #0] mapred.LocalJobRunner (LocalJobRunner.java:statusUpdate(591)) - map
2018-10-20 00:24:49,515 INFO  [LocalJobRunner Map Task Executor #0] mapred.Task (Task.java:sendDone(1121)) - Task 'attempt_local286846883_0006_m_000000_0' done.
2018-10-20 00:24:49,515 INFO  [LocalJobRunner Map Task Executor #0] mapred.LocalJobRunner (LocalJobRunner.java:run(249)) - Finishing task: attempt_local286846883_0006_m_000000_0
2018-10-20 00:24:49,515 INFO  [Thread-121] mapred.LocalJobRunner (LocalJobRunner.java:runTasks(456)) - map task executor complete.
2018-10-20 00:24:49,516 INFO  [Thread-121] mapred.LocalJobRunner (LocalJobRunner.java:runTasks(448)) - Waiting for reduce tasks
2018-10-20 00:24:49,522 INFO  [pool-18-thread-1] mapred.LocalJobRunner (LocalJobRunner.java:run(302)) - Starting task: attempt_local286846883_0006_r_000000_0
2018-10-20 00:24:49,523 INFO  [pool-18-thread-1] mapred.Task (Task.java:initialize(587)) -  Using ResourceCalculatorProcessTree : [ ]
2018-10-20 00:24:49,523 INFO  [pool-18-thread-1] mapred.ReduceTask (ReduceTask.java:run(362)) - Using ShuffleConsumerPlugin: org.apache.hadoop.mapreduce.task.reduce.Shuffle@54933de2
2018-10-20 00:24:49,530 INFO  [pool-18-thread-1] reduce.MergeManagerImpl (MergeManagerImpl.java:<init>(196)) - MergerManager: memoryLimit=677117952, maxSingleShuffleLimit=169279488, mergeThreshold=446897856, ioSortFactor=10, memToMemMergeOutputsThreshold=10
2018-10-20 00:24:49,531 INFO  [EventFetcher for fetching Map Completion Events] reduce.EventFetcher (EventFetcher.java:run(61)) - attempt_local286846883_0006_r_000000_0 Thread started: EventFetcher for fetching Map Completion Events
2018-10-20 00:24:49,532 INFO  [localfetcher#6] reduce.LocalFetcher (LocalFetcher.java:copyMapOutput(141)) - localfetcher#6 about to shuffle output of map attempt_local286846883_0006_m_000000_0 decomp: 2 len: 6 to MEMORY
2018-10-20 00:24:49,532 INFO  [localfetcher#6] reduce.InMemoryMapOutput (InMemoryMapOutput.java:shuffle(100)) - Read 2 bytes from map-output for attempt_local286846883_0006_m_000000_0
2018-10-20 00:24:49,532 INFO  [localfetcher#6] reduce.MergeManagerImpl (MergeManagerImpl.java:closeInMemoryFile(314)) - closeInMemoryFile -> map-output of size: 2, inMemoryMapOutputs.size() -> 1, commitMemory -> 0, usedMemory ->2
2018-10-20 00:24:49,532 INFO  [EventFetcher for fetching Map Completion Events] reduce.EventFetcher (EventFetcher.java:run(76)) - EventFetcher is interrupted.. Returning
2018-10-20 00:24:49,533 INFO  [pool-18-thread-1] mapred.LocalJobRunner (LocalJobRunner.java:statusUpdate(591)) - 1 / 1 copied.
2018-10-20 00:24:49,533 INFO  [pool-18-thread-1] reduce.MergeManagerImpl (MergeManagerImpl.java:finalMerge(674)) - finalMerge called with 1 in-memory map-outputs and 0 on-disk map-outputs
2018-10-20 00:24:49,533 INFO  [pool-18-thread-1] mapred.Merger (Merger.java:merge(597)) - Merging 1 sorted segments
2018-10-20 00:24:49,534 INFO  [pool-18-thread-1] mapred.Merger (Merger.java:merge(696)) - Down to the last merge-pass, with 0 segments left of total size: 0 bytes
2018-10-20 00:24:49,534 INFO  [pool-18-thread-1] reduce.MergeManagerImpl (MergeManagerImpl.java:finalMerge(751)) - Merged 1 segments, 2 bytes to disk to satisfy reduce memory limit
2018-10-20 00:24:49,534 INFO  [pool-18-thread-1] reduce.MergeManagerImpl (MergeManagerImpl.java:finalMerge(781)) - Merging 1 files, 6 bytes from disk
2018-10-20 00:24:49,534 INFO  [pool-18-thread-1] reduce.MergeManagerImpl (MergeManagerImpl.java:finalMerge(796)) - Merging 0 segments, 0 bytes from memory into reduce
2018-10-20 00:24:49,534 INFO  [pool-18-thread-1] mapred.Merger (Merger.java:merge(597)) - Merging 1 sorted segments
2018-10-20 00:24:49,535 INFO  [pool-18-thread-1] mapred.Merger (Merger.java:merge(696)) - Down to the last merge-pass, with 0 segments left of total size: 0 bytes
2018-10-20 00:24:49,535 INFO  [pool-18-thread-1] mapred.LocalJobRunner (LocalJobRunner.java:statusUpdate(591)) - 1 / 1 copied.
2018-10-20 00:24:49,546 INFO  [pool-18-thread-1] mapred.Task (Task.java:done(1001)) - Task:attempt_local286846883_0006_r_000000_0 is done. And is in the process of committing
2018-10-20 00:24:49,546 INFO  [pool-18-thread-1] mapred.LocalJobRunner (LocalJobRunner.java:statusUpdate(591)) - 1 / 1 copied.
2018-10-20 00:24:49,546 INFO  [pool-18-thread-1] mapred.Task (Task.java:commit(1162)) - Task attempt_local286846883_0006_r_000000_0 is allowed to commit now
2018-10-20 00:24:49,548 INFO  [pool-18-thread-1] output.FileOutputCommitter (FileOutputCommitter.java:commitTask(439)) - Saved output of task 'attempt_local286846883_0006_r_000000_0' to file:/home/ptrivedi/project3/intermediate/i5/_temporary/0/task_local286846883_0006_r_000000
2018-10-20 00:24:49,549 INFO  [pool-18-thread-1] mapred.LocalJobRunner (LocalJobRunner.java:statusUpdate(591)) - reduce > reduce
2018-10-20 00:24:49,549 INFO  [pool-18-thread-1] mapred.Task (Task.java:sendDone(1121)) - Task 'attempt_local286846883_0006_r_000000_0' done.
2018-10-20 00:24:49,549 INFO  [pool-18-thread-1] mapred.LocalJobRunner (LocalJobRunner.java:run(325)) - Finishing task: attempt_local286846883_0006_r_000000_0
2018-10-20 00:24:49,549 INFO  [Thread-121] mapred.LocalJobRunner (LocalJobRunner.java:runTasks(456)) - reduce task executor complete.
2018-10-20 00:24:50,336 INFO  [main] mapreduce.Job (Job.java:monitorAndPrintJob(1366)) - Job job_local286846883_0006 running in uber mode : false
2018-10-20 00:24:50,337 INFO  [main] mapreduce.Job (Job.java:monitorAndPrintJob(1373)) -  map 100% reduce 100%
2018-10-20 00:24:50,337 INFO  [main] mapreduce.Job (Job.java:monitorAndPrintJob(1384)) - Job job_local286846883_0006 completed successfully
2018-10-20 00:24:50,338 INFO  [main] mapreduce.Job (Job.java:monitorAndPrintJob(1391)) - Counters: 33
	File System Counters
		FILE: Number of bytes read=116552
		FILE: Number of bytes written=3174339
		FILE: Number of read operations=0
		FILE: Number of large read operations=0
		FILE: Number of write operations=0
	Map-Reduce Framework
		Map input records=0
		Map output records=0
		Map output bytes=0
		Map output materialized bytes=6
		Input split bytes=122
		Combine input records=0
		Combine output records=0
		Reduce input groups=0
		Reduce shuffle bytes=6
		Reduce input records=0
		Reduce output records=0
		Spilled Records=0
		Shuffled Maps =1
		Failed Shuffles=0
		Merged Map outputs=1
		GC time elapsed (ms)=103
		CPU time spent (ms)=0
		Physical memory (bytes) snapshot=0
		Virtual memory (bytes) snapshot=0
		Total committed heap usage (bytes)=1934622720
	Shuffle Errors
		BAD_ID=0
		CONNECTION=0
		IO_ERROR=0
		WRONG_LENGTH=0
		WRONG_MAP=0
		WRONG_REDUCE=0
	File Input Format Counters 
		Bytes Read=79
	File Output Format Counters 
		Bytes Written=79
2018-10-20 00:24:50,349 INFO  [main] jvm.JvmMetrics (JvmMetrics.java:init(71)) - Cannot initialize JVM Metrics with processName=JobTracker, sessionId= - already initialized
2018-10-20 00:24:50,370 WARN  [main] mapreduce.JobSubmitter (JobSubmitter.java:copyAndConfigureFiles(153)) - Hadoop command-line option parsing not performed. Implement the Tool interface and execute your application with ToolRunner to remedy this.
2018-10-20 00:24:50,395 INFO  [main] input.FileInputFormat (FileInputFormat.java:listStatus(281)) - Total input paths to process : 1
2018-10-20 00:24:50,404 INFO  [main] mapreduce.JobSubmitter (JobSubmitter.java:submitJobInternal(494)) - number of splits:1
2018-10-20 00:24:50,413 INFO  [main] mapreduce.JobSubmitter (JobSubmitter.java:printTokens(583)) - Submitting tokens for job: job_local130082689_0007
2018-10-20 00:24:50,465 INFO  [main] mapreduce.Job (Job.java:submit(1300)) - The url to track the job: http://localhost:8080/
2018-10-20 00:24:50,465 INFO  [main] mapreduce.Job (Job.java:monitorAndPrintJob(1345)) - Running job: job_local130082689_0007
2018-10-20 00:24:50,466 INFO  [Thread-143] mapred.LocalJobRunner (LocalJobRunner.java:createOutputCommitter(471)) - OutputCommitter set in config null
2018-10-20 00:24:50,466 INFO  [Thread-143] mapred.LocalJobRunner (LocalJobRunner.java:createOutputCommitter(489)) - OutputCommitter is org.apache.hadoop.mapreduce.lib.output.FileOutputCommitter
2018-10-20 00:24:50,471 INFO  [Thread-143] mapred.LocalJobRunner (LocalJobRunner.java:runTasks(448)) - Waiting for map tasks
2018-10-20 00:24:50,471 INFO  [LocalJobRunner Map Task Executor #0] mapred.LocalJobRunner (LocalJobRunner.java:run(224)) - Starting task: attempt_local130082689_0007_m_000000_0
2018-10-20 00:24:50,473 INFO  [LocalJobRunner Map Task Executor #0] mapred.Task (Task.java:initialize(587)) -  Using ResourceCalculatorProcessTree : [ ]
2018-10-20 00:24:50,473 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:runNewMapper(753)) - Processing split: file:/home/ptrivedi/project3/intermediate/i5/part-r-00000:0+67
2018-10-20 00:24:50,615 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:setEquator(1202)) - (EQUATOR) 0 kvi 26214396(104857584)
2018-10-20 00:24:50,615 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:init(995)) - mapreduce.task.io.sort.mb: 100
2018-10-20 00:24:50,615 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:init(996)) - soft limit at 83886080
2018-10-20 00:24:50,615 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:init(997)) - bufstart = 0; bufvoid = 104857600
2018-10-20 00:24:50,615 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:init(998)) - kvstart = 26214396; length = 6553600
2018-10-20 00:24:50,616 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:createSortingCollector(402)) - Map output collector class = org.apache.hadoop.mapred.MapTask$MapOutputBuffer
2018-10-20 00:24:50,620 INFO  [LocalJobRunner Map Task Executor #0] mapred.LocalJobRunner (LocalJobRunner.java:statusUpdate(591)) - 
2018-10-20 00:24:50,622 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:flush(1457)) - Starting flush of map output
2018-10-20 00:24:50,623 INFO  [LocalJobRunner Map Task Executor #0] mapred.Task (Task.java:done(1001)) - Task:attempt_local130082689_0007_m_000000_0 is done. And is in the process of committing
2018-10-20 00:24:50,625 INFO  [LocalJobRunner Map Task Executor #0] mapred.LocalJobRunner (LocalJobRunner.java:statusUpdate(591)) - map
2018-10-20 00:24:50,625 INFO  [LocalJobRunner Map Task Executor #0] mapred.Task (Task.java:sendDone(1121)) - Task 'attempt_local130082689_0007_m_000000_0' done.
2018-10-20 00:24:50,625 INFO  [LocalJobRunner Map Task Executor #0] mapred.LocalJobRunner (LocalJobRunner.java:run(249)) - Finishing task: attempt_local130082689_0007_m_000000_0
2018-10-20 00:24:50,625 INFO  [Thread-143] mapred.LocalJobRunner (LocalJobRunner.java:runTasks(456)) - map task executor complete.
2018-10-20 00:24:50,626 INFO  [Thread-143] mapred.LocalJobRunner (LocalJobRunner.java:runTasks(448)) - Waiting for reduce tasks
2018-10-20 00:24:50,632 INFO  [pool-21-thread-1] mapred.LocalJobRunner (LocalJobRunner.java:run(302)) - Starting task: attempt_local130082689_0007_r_000000_0
2018-10-20 00:24:50,633 INFO  [pool-21-thread-1] mapred.Task (Task.java:initialize(587)) -  Using ResourceCalculatorProcessTree : [ ]
2018-10-20 00:24:50,634 INFO  [pool-21-thread-1] mapred.ReduceTask (ReduceTask.java:run(362)) - Using ShuffleConsumerPlugin: org.apache.hadoop.mapreduce.task.reduce.Shuffle@7c6c790a
2018-10-20 00:24:50,637 INFO  [pool-21-thread-1] reduce.MergeManagerImpl (MergeManagerImpl.java:<init>(196)) - MergerManager: memoryLimit=695468032, maxSingleShuffleLimit=173867008, mergeThreshold=459008928, ioSortFactor=10, memToMemMergeOutputsThreshold=10
2018-10-20 00:24:50,637 INFO  [EventFetcher for fetching Map Completion Events] reduce.EventFetcher (EventFetcher.java:run(61)) - attempt_local130082689_0007_r_000000_0 Thread started: EventFetcher for fetching Map Completion Events
2018-10-20 00:24:50,638 INFO  [localfetcher#7] reduce.LocalFetcher (LocalFetcher.java:copyMapOutput(141)) - localfetcher#7 about to shuffle output of map attempt_local130082689_0007_m_000000_0 decomp: 2 len: 6 to MEMORY
2018-10-20 00:24:50,638 INFO  [localfetcher#7] reduce.InMemoryMapOutput (InMemoryMapOutput.java:shuffle(100)) - Read 2 bytes from map-output for attempt_local130082689_0007_m_000000_0
2018-10-20 00:24:50,638 INFO  [localfetcher#7] reduce.MergeManagerImpl (MergeManagerImpl.java:closeInMemoryFile(314)) - closeInMemoryFile -> map-output of size: 2, inMemoryMapOutputs.size() -> 1, commitMemory -> 0, usedMemory ->2
2018-10-20 00:24:50,639 INFO  [EventFetcher for fetching Map Completion Events] reduce.EventFetcher (EventFetcher.java:run(76)) - EventFetcher is interrupted.. Returning
2018-10-20 00:24:50,639 INFO  [pool-21-thread-1] mapred.LocalJobRunner (LocalJobRunner.java:statusUpdate(591)) - 1 / 1 copied.
2018-10-20 00:24:50,639 INFO  [pool-21-thread-1] reduce.MergeManagerImpl (MergeManagerImpl.java:finalMerge(674)) - finalMerge called with 1 in-memory map-outputs and 0 on-disk map-outputs
2018-10-20 00:24:50,640 INFO  [pool-21-thread-1] mapred.Merger (Merger.java:merge(597)) - Merging 1 sorted segments
2018-10-20 00:24:50,643 INFO  [pool-21-thread-1] mapred.Merger (Merger.java:merge(696)) - Down to the last merge-pass, with 0 segments left of total size: 0 bytes
2018-10-20 00:24:50,644 INFO  [pool-21-thread-1] reduce.MergeManagerImpl (MergeManagerImpl.java:finalMerge(751)) - Merged 1 segments, 2 bytes to disk to satisfy reduce memory limit
2018-10-20 00:24:50,644 INFO  [pool-21-thread-1] reduce.MergeManagerImpl (MergeManagerImpl.java:finalMerge(781)) - Merging 1 files, 6 bytes from disk
2018-10-20 00:24:50,644 INFO  [pool-21-thread-1] reduce.MergeManagerImpl (MergeManagerImpl.java:finalMerge(796)) - Merging 0 segments, 0 bytes from memory into reduce
2018-10-20 00:24:50,644 INFO  [pool-21-thread-1] mapred.Merger (Merger.java:merge(597)) - Merging 1 sorted segments
2018-10-20 00:24:50,644 INFO  [pool-21-thread-1] mapred.Merger (Merger.java:merge(696)) - Down to the last merge-pass, with 0 segments left of total size: 0 bytes
2018-10-20 00:24:50,644 INFO  [pool-21-thread-1] mapred.LocalJobRunner (LocalJobRunner.java:statusUpdate(591)) - 1 / 1 copied.
2018-10-20 00:24:50,657 INFO  [pool-21-thread-1] mapred.Task (Task.java:done(1001)) - Task:attempt_local130082689_0007_r_000000_0 is done. And is in the process of committing
2018-10-20 00:24:50,658 INFO  [pool-21-thread-1] mapred.LocalJobRunner (LocalJobRunner.java:statusUpdate(591)) - 1 / 1 copied.
2018-10-20 00:24:50,658 INFO  [pool-21-thread-1] mapred.Task (Task.java:commit(1162)) - Task attempt_local130082689_0007_r_000000_0 is allowed to commit now
2018-10-20 00:24:50,661 INFO  [pool-21-thread-1] output.FileOutputCommitter (FileOutputCommitter.java:commitTask(439)) - Saved output of task 'attempt_local130082689_0007_r_000000_0' to file:/home/ptrivedi/project3/intermediate/i6/_temporary/0/task_local130082689_0007_r_000000
2018-10-20 00:24:50,662 INFO  [pool-21-thread-1] mapred.LocalJobRunner (LocalJobRunner.java:statusUpdate(591)) - reduce > reduce
2018-10-20 00:24:50,662 INFO  [pool-21-thread-1] mapred.Task (Task.java:sendDone(1121)) - Task 'attempt_local130082689_0007_r_000000_0' done.
2018-10-20 00:24:50,662 INFO  [pool-21-thread-1] mapred.LocalJobRunner (LocalJobRunner.java:run(325)) - Finishing task: attempt_local130082689_0007_r_000000_0
2018-10-20 00:24:50,662 INFO  [Thread-143] mapred.LocalJobRunner (LocalJobRunner.java:runTasks(456)) - reduce task executor complete.
2018-10-20 00:24:51,465 INFO  [main] mapreduce.Job (Job.java:monitorAndPrintJob(1366)) - Job job_local130082689_0007 running in uber mode : false
2018-10-20 00:24:51,466 INFO  [main] mapreduce.Job (Job.java:monitorAndPrintJob(1373)) -  map 100% reduce 100%
2018-10-20 00:24:51,466 INFO  [main] mapreduce.Job (Job.java:monitorAndPrintJob(1384)) - Job job_local130082689_0007 completed successfully
2018-10-20 00:24:51,476 INFO  [main] mapreduce.Job (Job.java:monitorAndPrintJob(1391)) - Counters: 33
	File System Counters
		FILE: Number of bytes read=133732
		FILE: Number of bytes written=3701027
		FILE: Number of read operations=0
		FILE: Number of large read operations=0
		FILE: Number of write operations=0
	Map-Reduce Framework
		Map input records=0
		Map output records=0
		Map output bytes=0
		Map output materialized bytes=6
		Input split bytes=122
		Combine input records=0
		Combine output records=0
		Reduce input groups=0
		Reduce shuffle bytes=6
		Reduce input records=0
		Reduce output records=0
		Spilled Records=0
		Shuffled Maps =1
		Failed Shuffles=0
		Merged Map outputs=1
		GC time elapsed (ms)=109
		CPU time spent (ms)=0
		Physical memory (bytes) snapshot=0
		Virtual memory (bytes) snapshot=0
		Total committed heap usage (bytes)=1987051520
	Shuffle Errors
		BAD_ID=0
		CONNECTION=0
		IO_ERROR=0
		WRONG_LENGTH=0
		WRONG_MAP=0
		WRONG_REDUCE=0
	File Input Format Counters 
		Bytes Read=79
	File Output Format Counters 
		Bytes Written=79
2018-10-20 00:24:51,494 INFO  [main] jvm.JvmMetrics (JvmMetrics.java:init(71)) - Cannot initialize JVM Metrics with processName=JobTracker, sessionId= - already initialized
2018-10-20 00:24:51,504 WARN  [main] mapreduce.JobSubmitter (JobSubmitter.java:copyAndConfigureFiles(153)) - Hadoop command-line option parsing not performed. Implement the Tool interface and execute your application with ToolRunner to remedy this.
2018-10-20 00:24:51,534 INFO  [main] input.FileInputFormat (FileInputFormat.java:listStatus(281)) - Total input paths to process : 1
2018-10-20 00:24:51,547 INFO  [main] mapreduce.JobSubmitter (JobSubmitter.java:submitJobInternal(494)) - number of splits:1
2018-10-20 00:24:51,555 INFO  [main] mapreduce.JobSubmitter (JobSubmitter.java:printTokens(583)) - Submitting tokens for job: job_local1734618657_0008
2018-10-20 00:24:51,641 INFO  [main] mapreduce.Job (Job.java:submit(1300)) - The url to track the job: http://localhost:8080/
2018-10-20 00:24:51,642 INFO  [main] mapreduce.Job (Job.java:monitorAndPrintJob(1345)) - Running job: job_local1734618657_0008
2018-10-20 00:24:51,642 INFO  [Thread-165] mapred.LocalJobRunner (LocalJobRunner.java:createOutputCommitter(471)) - OutputCommitter set in config null
2018-10-20 00:24:51,643 INFO  [Thread-165] mapred.LocalJobRunner (LocalJobRunner.java:createOutputCommitter(489)) - OutputCommitter is org.apache.hadoop.mapreduce.lib.output.FileOutputCommitter
2018-10-20 00:24:51,666 INFO  [Thread-165] mapred.LocalJobRunner (LocalJobRunner.java:runTasks(448)) - Waiting for map tasks
2018-10-20 00:24:51,667 INFO  [LocalJobRunner Map Task Executor #0] mapred.LocalJobRunner (LocalJobRunner.java:run(224)) - Starting task: attempt_local1734618657_0008_m_000000_0
2018-10-20 00:24:51,667 INFO  [LocalJobRunner Map Task Executor #0] mapred.Task (Task.java:initialize(587)) -  Using ResourceCalculatorProcessTree : [ ]
2018-10-20 00:24:51,668 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:runNewMapper(753)) - Processing split: file:/home/ptrivedi/project3/intermediate/i6/part-r-00000:0+67
2018-10-20 00:24:51,686 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:setEquator(1202)) - (EQUATOR) 0 kvi 26214396(104857584)
2018-10-20 00:24:51,687 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:init(995)) - mapreduce.task.io.sort.mb: 100
2018-10-20 00:24:51,687 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:init(996)) - soft limit at 83886080
2018-10-20 00:24:51,687 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:init(997)) - bufstart = 0; bufvoid = 104857600
2018-10-20 00:24:51,687 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:init(998)) - kvstart = 26214396; length = 6553600
2018-10-20 00:24:51,688 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:createSortingCollector(402)) - Map output collector class = org.apache.hadoop.mapred.MapTask$MapOutputBuffer
2018-10-20 00:24:51,691 INFO  [LocalJobRunner Map Task Executor #0] mapred.LocalJobRunner (LocalJobRunner.java:statusUpdate(591)) - 
2018-10-20 00:24:51,691 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:flush(1457)) - Starting flush of map output
2018-10-20 00:24:51,692 INFO  [LocalJobRunner Map Task Executor #0] mapred.Task (Task.java:done(1001)) - Task:attempt_local1734618657_0008_m_000000_0 is done. And is in the process of committing
2018-10-20 00:24:51,698 INFO  [LocalJobRunner Map Task Executor #0] mapred.LocalJobRunner (LocalJobRunner.java:statusUpdate(591)) - map
2018-10-20 00:24:51,698 INFO  [LocalJobRunner Map Task Executor #0] mapred.Task (Task.java:sendDone(1121)) - Task 'attempt_local1734618657_0008_m_000000_0' done.
2018-10-20 00:24:51,698 INFO  [LocalJobRunner Map Task Executor #0] mapred.LocalJobRunner (LocalJobRunner.java:run(249)) - Finishing task: attempt_local1734618657_0008_m_000000_0
2018-10-20 00:24:51,698 INFO  [Thread-165] mapred.LocalJobRunner (LocalJobRunner.java:runTasks(456)) - map task executor complete.
2018-10-20 00:24:51,699 INFO  [Thread-165] mapred.LocalJobRunner (LocalJobRunner.java:runTasks(448)) - Waiting for reduce tasks
2018-10-20 00:24:51,705 INFO  [pool-24-thread-1] mapred.LocalJobRunner (LocalJobRunner.java:run(302)) - Starting task: attempt_local1734618657_0008_r_000000_0
2018-10-20 00:24:51,707 INFO  [pool-24-thread-1] mapred.Task (Task.java:initialize(587)) -  Using ResourceCalculatorProcessTree : [ ]
2018-10-20 00:24:51,707 INFO  [pool-24-thread-1] mapred.ReduceTask (ReduceTask.java:run(362)) - Using ShuffleConsumerPlugin: org.apache.hadoop.mapreduce.task.reduce.Shuffle@59d71d73
2018-10-20 00:24:51,710 INFO  [pool-24-thread-1] reduce.MergeManagerImpl (MergeManagerImpl.java:<init>(196)) - MergerManager: memoryLimit=695468032, maxSingleShuffleLimit=173867008, mergeThreshold=459008928, ioSortFactor=10, memToMemMergeOutputsThreshold=10
2018-10-20 00:24:51,716 INFO  [EventFetcher for fetching Map Completion Events] reduce.EventFetcher (EventFetcher.java:run(61)) - attempt_local1734618657_0008_r_000000_0 Thread started: EventFetcher for fetching Map Completion Events
2018-10-20 00:24:51,717 INFO  [localfetcher#8] reduce.LocalFetcher (LocalFetcher.java:copyMapOutput(141)) - localfetcher#8 about to shuffle output of map attempt_local1734618657_0008_m_000000_0 decomp: 2 len: 6 to MEMORY
2018-10-20 00:24:51,717 INFO  [localfetcher#8] reduce.InMemoryMapOutput (InMemoryMapOutput.java:shuffle(100)) - Read 2 bytes from map-output for attempt_local1734618657_0008_m_000000_0
2018-10-20 00:24:51,717 INFO  [localfetcher#8] reduce.MergeManagerImpl (MergeManagerImpl.java:closeInMemoryFile(314)) - closeInMemoryFile -> map-output of size: 2, inMemoryMapOutputs.size() -> 1, commitMemory -> 0, usedMemory ->2
2018-10-20 00:24:51,717 INFO  [EventFetcher for fetching Map Completion Events] reduce.EventFetcher (EventFetcher.java:run(76)) - EventFetcher is interrupted.. Returning
2018-10-20 00:24:51,718 INFO  [pool-24-thread-1] mapred.LocalJobRunner (LocalJobRunner.java:statusUpdate(591)) - 1 / 1 copied.
2018-10-20 00:24:51,718 INFO  [pool-24-thread-1] reduce.MergeManagerImpl (MergeManagerImpl.java:finalMerge(674)) - finalMerge called with 1 in-memory map-outputs and 0 on-disk map-outputs
2018-10-20 00:24:51,718 INFO  [pool-24-thread-1] mapred.Merger (Merger.java:merge(597)) - Merging 1 sorted segments
2018-10-20 00:24:51,719 INFO  [pool-24-thread-1] mapred.Merger (Merger.java:merge(696)) - Down to the last merge-pass, with 0 segments left of total size: 0 bytes
2018-10-20 00:24:51,720 INFO  [pool-24-thread-1] reduce.MergeManagerImpl (MergeManagerImpl.java:finalMerge(751)) - Merged 1 segments, 2 bytes to disk to satisfy reduce memory limit
2018-10-20 00:24:51,720 INFO  [pool-24-thread-1] reduce.MergeManagerImpl (MergeManagerImpl.java:finalMerge(781)) - Merging 1 files, 6 bytes from disk
2018-10-20 00:24:51,720 INFO  [pool-24-thread-1] reduce.MergeManagerImpl (MergeManagerImpl.java:finalMerge(796)) - Merging 0 segments, 0 bytes from memory into reduce
2018-10-20 00:24:51,720 INFO  [pool-24-thread-1] mapred.Merger (Merger.java:merge(597)) - Merging 1 sorted segments
2018-10-20 00:24:51,720 INFO  [pool-24-thread-1] mapred.Merger (Merger.java:merge(696)) - Down to the last merge-pass, with 0 segments left of total size: 0 bytes
2018-10-20 00:24:51,720 INFO  [pool-24-thread-1] mapred.LocalJobRunner (LocalJobRunner.java:statusUpdate(591)) - 1 / 1 copied.
2018-10-20 00:24:51,730 INFO  [pool-24-thread-1] mapred.Task (Task.java:done(1001)) - Task:attempt_local1734618657_0008_r_000000_0 is done. And is in the process of committing
2018-10-20 00:24:51,730 INFO  [pool-24-thread-1] mapred.LocalJobRunner (LocalJobRunner.java:statusUpdate(591)) - 1 / 1 copied.
2018-10-20 00:24:51,730 INFO  [pool-24-thread-1] mapred.Task (Task.java:commit(1162)) - Task attempt_local1734618657_0008_r_000000_0 is allowed to commit now
2018-10-20 00:24:51,731 INFO  [pool-24-thread-1] output.FileOutputCommitter (FileOutputCommitter.java:commitTask(439)) - Saved output of task 'attempt_local1734618657_0008_r_000000_0' to file:/home/ptrivedi/project3/intermediate/i7/_temporary/0/task_local1734618657_0008_r_000000
2018-10-20 00:24:51,732 INFO  [pool-24-thread-1] mapred.LocalJobRunner (LocalJobRunner.java:statusUpdate(591)) - reduce > reduce
2018-10-20 00:24:51,732 INFO  [pool-24-thread-1] mapred.Task (Task.java:sendDone(1121)) - Task 'attempt_local1734618657_0008_r_000000_0' done.
2018-10-20 00:24:51,732 INFO  [pool-24-thread-1] mapred.LocalJobRunner (LocalJobRunner.java:run(325)) - Finishing task: attempt_local1734618657_0008_r_000000_0
2018-10-20 00:24:51,732 INFO  [Thread-165] mapred.LocalJobRunner (LocalJobRunner.java:runTasks(456)) - reduce task executor complete.
2018-10-20 00:24:52,643 INFO  [main] mapreduce.Job (Job.java:monitorAndPrintJob(1366)) - Job job_local1734618657_0008 running in uber mode : false
2018-10-20 00:24:52,643 INFO  [main] mapreduce.Job (Job.java:monitorAndPrintJob(1373)) -  map 100% reduce 100%
2018-10-20 00:24:52,643 INFO  [main] mapreduce.Job (Job.java:monitorAndPrintJob(1384)) - Job job_local1734618657_0008 completed successfully
2018-10-20 00:24:52,644 INFO  [main] mapreduce.Job (Job.java:monitorAndPrintJob(1391)) - Counters: 33
	File System Counters
		FILE: Number of bytes read=150912
		FILE: Number of bytes written=4230435
		FILE: Number of read operations=0
		FILE: Number of large read operations=0
		FILE: Number of write operations=0
	Map-Reduce Framework
		Map input records=0
		Map output records=0
		Map output bytes=0
		Map output materialized bytes=6
		Input split bytes=122
		Combine input records=0
		Combine output records=0
		Reduce input groups=0
		Reduce shuffle bytes=6
		Reduce input records=0
		Reduce output records=0
		Spilled Records=0
		Shuffled Maps =1
		Failed Shuffles=0
		Merged Map outputs=1
		GC time elapsed (ms)=0
		CPU time spent (ms)=0
		Physical memory (bytes) snapshot=0
		Virtual memory (bytes) snapshot=0
		Total committed heap usage (bytes)=1987051520
	Shuffle Errors
		BAD_ID=0
		CONNECTION=0
		IO_ERROR=0
		WRONG_LENGTH=0
		WRONG_MAP=0
		WRONG_REDUCE=0
	File Input Format Counters 
		Bytes Read=79
	File Output Format Counters 
		Bytes Written=79
2018-10-20 00:24:52,657 INFO  [main] jvm.JvmMetrics (JvmMetrics.java:init(71)) - Cannot initialize JVM Metrics with processName=JobTracker, sessionId= - already initialized
2018-10-20 00:24:52,668 WARN  [main] mapreduce.JobSubmitter (JobSubmitter.java:copyAndConfigureFiles(153)) - Hadoop command-line option parsing not performed. Implement the Tool interface and execute your application with ToolRunner to remedy this.
2018-10-20 00:24:52,693 INFO  [main] input.FileInputFormat (FileInputFormat.java:listStatus(281)) - Total input paths to process : 1
2018-10-20 00:24:52,709 INFO  [main] mapreduce.JobSubmitter (JobSubmitter.java:submitJobInternal(494)) - number of splits:1
2018-10-20 00:24:52,718 INFO  [main] mapreduce.JobSubmitter (JobSubmitter.java:printTokens(583)) - Submitting tokens for job: job_local198279221_0009
2018-10-20 00:24:52,766 INFO  [main] mapreduce.Job (Job.java:submit(1300)) - The url to track the job: http://localhost:8080/
2018-10-20 00:24:52,766 INFO  [main] mapreduce.Job (Job.java:monitorAndPrintJob(1345)) - Running job: job_local198279221_0009
2018-10-20 00:24:52,767 INFO  [Thread-187] mapred.LocalJobRunner (LocalJobRunner.java:createOutputCommitter(471)) - OutputCommitter set in config null
2018-10-20 00:24:52,767 INFO  [Thread-187] mapred.LocalJobRunner (LocalJobRunner.java:createOutputCommitter(489)) - OutputCommitter is org.apache.hadoop.mapreduce.lib.output.FileOutputCommitter
2018-10-20 00:24:52,771 INFO  [Thread-187] mapred.LocalJobRunner (LocalJobRunner.java:runTasks(448)) - Waiting for map tasks
2018-10-20 00:24:52,771 INFO  [LocalJobRunner Map Task Executor #0] mapred.LocalJobRunner (LocalJobRunner.java:run(224)) - Starting task: attempt_local198279221_0009_m_000000_0
2018-10-20 00:24:52,773 INFO  [LocalJobRunner Map Task Executor #0] mapred.Task (Task.java:initialize(587)) -  Using ResourceCalculatorProcessTree : [ ]
2018-10-20 00:24:52,773 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:runNewMapper(753)) - Processing split: file:/home/ptrivedi/project3/intermediate/i7/part-r-00000:0+67
2018-10-20 00:24:52,785 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:setEquator(1202)) - (EQUATOR) 0 kvi 26214396(104857584)
2018-10-20 00:24:52,785 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:init(995)) - mapreduce.task.io.sort.mb: 100
2018-10-20 00:24:52,785 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:init(996)) - soft limit at 83886080
2018-10-20 00:24:52,785 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:init(997)) - bufstart = 0; bufvoid = 104857600
2018-10-20 00:24:52,785 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:init(998)) - kvstart = 26214396; length = 6553600
2018-10-20 00:24:52,786 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:createSortingCollector(402)) - Map output collector class = org.apache.hadoop.mapred.MapTask$MapOutputBuffer
2018-10-20 00:24:52,788 INFO  [LocalJobRunner Map Task Executor #0] mapred.LocalJobRunner (LocalJobRunner.java:statusUpdate(591)) - 
2018-10-20 00:24:52,788 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:flush(1457)) - Starting flush of map output
2018-10-20 00:24:52,789 INFO  [LocalJobRunner Map Task Executor #0] mapred.Task (Task.java:done(1001)) - Task:attempt_local198279221_0009_m_000000_0 is done. And is in the process of committing
2018-10-20 00:24:52,791 INFO  [LocalJobRunner Map Task Executor #0] mapred.LocalJobRunner (LocalJobRunner.java:statusUpdate(591)) - map
2018-10-20 00:24:52,791 INFO  [LocalJobRunner Map Task Executor #0] mapred.Task (Task.java:sendDone(1121)) - Task 'attempt_local198279221_0009_m_000000_0' done.
2018-10-20 00:24:52,791 INFO  [LocalJobRunner Map Task Executor #0] mapred.LocalJobRunner (LocalJobRunner.java:run(249)) - Finishing task: attempt_local198279221_0009_m_000000_0
2018-10-20 00:24:52,791 INFO  [Thread-187] mapred.LocalJobRunner (LocalJobRunner.java:runTasks(456)) - map task executor complete.
2018-10-20 00:24:52,792 INFO  [Thread-187] mapred.LocalJobRunner (LocalJobRunner.java:runTasks(448)) - Waiting for reduce tasks
2018-10-20 00:24:52,798 INFO  [pool-27-thread-1] mapred.LocalJobRunner (LocalJobRunner.java:run(302)) - Starting task: attempt_local198279221_0009_r_000000_0
2018-10-20 00:24:52,799 INFO  [pool-27-thread-1] mapred.Task (Task.java:initialize(587)) -  Using ResourceCalculatorProcessTree : [ ]
2018-10-20 00:24:52,799 INFO  [pool-27-thread-1] mapred.ReduceTask (ReduceTask.java:run(362)) - Using ShuffleConsumerPlugin: org.apache.hadoop.mapreduce.task.reduce.Shuffle@96e0b7a
2018-10-20 00:24:52,803 INFO  [pool-27-thread-1] reduce.MergeManagerImpl (MergeManagerImpl.java:<init>(196)) - MergerManager: memoryLimit=695100992, maxSingleShuffleLimit=173775248, mergeThreshold=458766688, ioSortFactor=10, memToMemMergeOutputsThreshold=10
2018-10-20 00:24:52,804 INFO  [EventFetcher for fetching Map Completion Events] reduce.EventFetcher (EventFetcher.java:run(61)) - attempt_local198279221_0009_r_000000_0 Thread started: EventFetcher for fetching Map Completion Events
2018-10-20 00:24:52,805 INFO  [localfetcher#9] reduce.LocalFetcher (LocalFetcher.java:copyMapOutput(141)) - localfetcher#9 about to shuffle output of map attempt_local198279221_0009_m_000000_0 decomp: 2 len: 6 to MEMORY
2018-10-20 00:24:52,806 INFO  [localfetcher#9] reduce.InMemoryMapOutput (InMemoryMapOutput.java:shuffle(100)) - Read 2 bytes from map-output for attempt_local198279221_0009_m_000000_0
2018-10-20 00:24:52,806 INFO  [localfetcher#9] reduce.MergeManagerImpl (MergeManagerImpl.java:closeInMemoryFile(314)) - closeInMemoryFile -> map-output of size: 2, inMemoryMapOutputs.size() -> 1, commitMemory -> 0, usedMemory ->2
2018-10-20 00:24:52,807 INFO  [EventFetcher for fetching Map Completion Events] reduce.EventFetcher (EventFetcher.java:run(76)) - EventFetcher is interrupted.. Returning
2018-10-20 00:24:52,807 INFO  [pool-27-thread-1] mapred.LocalJobRunner (LocalJobRunner.java:statusUpdate(591)) - 1 / 1 copied.
2018-10-20 00:24:52,807 INFO  [pool-27-thread-1] reduce.MergeManagerImpl (MergeManagerImpl.java:finalMerge(674)) - finalMerge called with 1 in-memory map-outputs and 0 on-disk map-outputs
2018-10-20 00:24:52,808 INFO  [pool-27-thread-1] mapred.Merger (Merger.java:merge(597)) - Merging 1 sorted segments
2018-10-20 00:24:52,808 INFO  [pool-27-thread-1] mapred.Merger (Merger.java:merge(696)) - Down to the last merge-pass, with 0 segments left of total size: 0 bytes
2018-10-20 00:24:52,808 INFO  [pool-27-thread-1] reduce.MergeManagerImpl (MergeManagerImpl.java:finalMerge(751)) - Merged 1 segments, 2 bytes to disk to satisfy reduce memory limit
2018-10-20 00:24:52,809 INFO  [pool-27-thread-1] reduce.MergeManagerImpl (MergeManagerImpl.java:finalMerge(781)) - Merging 1 files, 6 bytes from disk
2018-10-20 00:24:52,809 INFO  [pool-27-thread-1] reduce.MergeManagerImpl (MergeManagerImpl.java:finalMerge(796)) - Merging 0 segments, 0 bytes from memory into reduce
2018-10-20 00:24:52,809 INFO  [pool-27-thread-1] mapred.Merger (Merger.java:merge(597)) - Merging 1 sorted segments
2018-10-20 00:24:52,809 INFO  [pool-27-thread-1] mapred.Merger (Merger.java:merge(696)) - Down to the last merge-pass, with 0 segments left of total size: 0 bytes
2018-10-20 00:24:52,809 INFO  [pool-27-thread-1] mapred.LocalJobRunner (LocalJobRunner.java:statusUpdate(591)) - 1 / 1 copied.
2018-10-20 00:24:52,819 INFO  [pool-27-thread-1] mapred.Task (Task.java:done(1001)) - Task:attempt_local198279221_0009_r_000000_0 is done. And is in the process of committing
2018-10-20 00:24:52,820 INFO  [pool-27-thread-1] mapred.LocalJobRunner (LocalJobRunner.java:statusUpdate(591)) - 1 / 1 copied.
2018-10-20 00:24:52,820 INFO  [pool-27-thread-1] mapred.Task (Task.java:commit(1162)) - Task attempt_local198279221_0009_r_000000_0 is allowed to commit now
2018-10-20 00:24:52,821 INFO  [pool-27-thread-1] output.FileOutputCommitter (FileOutputCommitter.java:commitTask(439)) - Saved output of task 'attempt_local198279221_0009_r_000000_0' to file:/home/ptrivedi/project3/intermediate/i8/_temporary/0/task_local198279221_0009_r_000000
2018-10-20 00:24:52,821 INFO  [pool-27-thread-1] mapred.LocalJobRunner (LocalJobRunner.java:statusUpdate(591)) - reduce > reduce
2018-10-20 00:24:52,821 INFO  [pool-27-thread-1] mapred.Task (Task.java:sendDone(1121)) - Task 'attempt_local198279221_0009_r_000000_0' done.
2018-10-20 00:24:52,821 INFO  [pool-27-thread-1] mapred.LocalJobRunner (LocalJobRunner.java:run(325)) - Finishing task: attempt_local198279221_0009_r_000000_0
2018-10-20 00:24:52,823 INFO  [Thread-187] mapred.LocalJobRunner (LocalJobRunner.java:runTasks(456)) - reduce task executor complete.
2018-10-20 00:24:53,767 INFO  [main] mapreduce.Job (Job.java:monitorAndPrintJob(1366)) - Job job_local198279221_0009 running in uber mode : false
2018-10-20 00:24:53,767 INFO  [main] mapreduce.Job (Job.java:monitorAndPrintJob(1373)) -  map 100% reduce 100%
2018-10-20 00:24:53,767 INFO  [main] mapreduce.Job (Job.java:monitorAndPrintJob(1384)) - Job job_local198279221_0009 completed successfully
2018-10-20 00:24:53,768 INFO  [main] mapreduce.Job (Job.java:monitorAndPrintJob(1391)) - Counters: 33
	File System Counters
		FILE: Number of bytes read=168092
		FILE: Number of bytes written=4757123
		FILE: Number of read operations=0
		FILE: Number of large read operations=0
		FILE: Number of write operations=0
	Map-Reduce Framework
		Map input records=0
		Map output records=0
		Map output bytes=0
		Map output materialized bytes=6
		Input split bytes=122
		Combine input records=0
		Combine output records=0
		Reduce input groups=0
		Reduce shuffle bytes=6
		Reduce input records=0
		Reduce output records=0
		Spilled Records=0
		Shuffled Maps =1
		Failed Shuffles=0
		Merged Map outputs=1
		GC time elapsed (ms)=0
		CPU time spent (ms)=0
		Physical memory (bytes) snapshot=0
		Virtual memory (bytes) snapshot=0
		Total committed heap usage (bytes)=1986002944
	Shuffle Errors
		BAD_ID=0
		CONNECTION=0
		IO_ERROR=0
		WRONG_LENGTH=0
		WRONG_MAP=0
		WRONG_REDUCE=0
	File Input Format Counters 
		Bytes Read=79
	File Output Format Counters 
		Bytes Written=79
2018-10-20 00:24:53,780 INFO  [main] mapreduce.Job (Job.java:monitorAndPrintJob(1345)) - Running job: job_local1075008924_0001
2018-10-20 00:24:53,780 INFO  [main] mapreduce.Job (Job.java:monitorAndPrintJob(1366)) - Job job_local1075008924_0001 running in uber mode : false
2018-10-20 00:24:53,780 INFO  [main] mapreduce.Job (Job.java:monitorAndPrintJob(1373)) -  map 100% reduce 67%
2018-10-20 00:24:53,780 INFO  [main] mapreduce.Job (Job.java:monitorAndPrintJob(1386)) - Job job_local1075008924_0001 failed with state FAILED due to: NA
2018-10-20 00:24:53,792 INFO  [main] mapreduce.Job (Job.java:monitorAndPrintJob(1391)) - Counters: 33
	File System Counters
		FILE: Number of bytes read=69996
		FILE: Number of bytes written=1851811
		FILE: Number of read operations=0
		FILE: Number of large read operations=0
		FILE: Number of write operations=0
	Map-Reduce Framework
		Map input records=64
		Map output records=64
		Map output bytes=1664
		Map output materialized bytes=1798
		Input split bytes=109
		Combine input records=0
		Combine output records=0
		Reduce input groups=1
		Reduce shuffle bytes=1798
		Reduce input records=0
		Reduce output records=0
		Spilled Records=64
		Shuffled Maps =1
		Failed Shuffles=0
		Merged Map outputs=1
		GC time elapsed (ms)=424
		CPU time spent (ms)=0
		Physical memory (bytes) snapshot=0
		Virtual memory (bytes) snapshot=0
		Total committed heap usage (bytes)=2010120192
	Shuffle Errors
		BAD_ID=0
		CONNECTION=0
		IO_ERROR=0
		WRONG_LENGTH=0
		WRONG_MAP=0
		WRONG_REDUCE=0
	File Input Format Counters 
		Bytes Read=3541
	File Output Format Counters 
		Bytes Written=79
2018-10-20 00:24:53,794 INFO  [main] jvm.JvmMetrics (JvmMetrics.java:init(71)) - Cannot initialize JVM Metrics with processName=JobTracker, sessionId= - already initialized
2018-10-20 00:24:53,804 WARN  [main] mapreduce.JobSubmitter (JobSubmitter.java:copyAndConfigureFiles(153)) - Hadoop command-line option parsing not performed. Implement the Tool interface and execute your application with ToolRunner to remedy this.
2018-10-20 00:24:53,829 INFO  [main] input.FileInputFormat (FileInputFormat.java:listStatus(281)) - Total input paths to process : 1
2018-10-20 00:24:53,841 INFO  [main] mapreduce.JobSubmitter (JobSubmitter.java:submitJobInternal(494)) - number of splits:1
2018-10-20 00:24:53,850 INFO  [main] mapreduce.JobSubmitter (JobSubmitter.java:printTokens(583)) - Submitting tokens for job: job_local908659401_0010
2018-10-20 00:24:53,909 INFO  [main] mapreduce.Job (Job.java:submit(1300)) - The url to track the job: http://localhost:8080/
2018-10-20 00:24:53,909 INFO  [main] mapreduce.Job (Job.java:monitorAndPrintJob(1345)) - Running job: job_local908659401_0010
2018-10-20 00:24:53,909 INFO  [Thread-209] mapred.LocalJobRunner (LocalJobRunner.java:createOutputCommitter(471)) - OutputCommitter set in config null
2018-10-20 00:24:53,909 INFO  [Thread-209] mapred.LocalJobRunner (LocalJobRunner.java:createOutputCommitter(489)) - OutputCommitter is org.apache.hadoop.mapreduce.lib.output.FileOutputCommitter
2018-10-20 00:24:53,914 INFO  [Thread-209] mapred.LocalJobRunner (LocalJobRunner.java:runTasks(448)) - Waiting for map tasks
2018-10-20 00:24:53,914 INFO  [LocalJobRunner Map Task Executor #0] mapred.LocalJobRunner (LocalJobRunner.java:run(224)) - Starting task: attempt_local908659401_0010_m_000000_0
2018-10-20 00:24:53,915 INFO  [LocalJobRunner Map Task Executor #0] mapred.Task (Task.java:initialize(587)) -  Using ResourceCalculatorProcessTree : [ ]
2018-10-20 00:24:53,916 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:runNewMapper(753)) - Processing split: file:/home/ptrivedi/project3/intermediate/i8/part-r-00000:0+67
2018-10-20 00:24:53,939 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:setEquator(1202)) - (EQUATOR) 0 kvi 26214396(104857584)
2018-10-20 00:24:53,939 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:init(995)) - mapreduce.task.io.sort.mb: 100
2018-10-20 00:24:53,939 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:init(996)) - soft limit at 83886080
2018-10-20 00:24:53,939 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:init(997)) - bufstart = 0; bufvoid = 104857600
2018-10-20 00:24:53,939 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:init(998)) - kvstart = 26214396; length = 6553600
2018-10-20 00:24:53,940 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:createSortingCollector(402)) - Map output collector class = org.apache.hadoop.mapred.MapTask$MapOutputBuffer
2018-10-20 00:24:53,942 INFO  [LocalJobRunner Map Task Executor #0] mapred.LocalJobRunner (LocalJobRunner.java:statusUpdate(591)) - 
2018-10-20 00:24:53,943 INFO  [LocalJobRunner Map Task Executor #0] mapred.MapTask (MapTask.java:flush(1457)) - Starting flush of map output
2018-10-20 00:24:53,944 INFO  [LocalJobRunner Map Task Executor #0] mapred.Task (Task.java:done(1001)) - Task:attempt_local908659401_0010_m_000000_0 is done. And is in the process of committing
2018-10-20 00:24:53,951 INFO  [LocalJobRunner Map Task Executor #0] mapred.LocalJobRunner (LocalJobRunner.java:statusUpdate(591)) - map
2018-10-20 00:24:53,951 INFO  [LocalJobRunner Map Task Executor #0] mapred.Task (Task.java:sendDone(1121)) - Task 'attempt_local908659401_0010_m_000000_0' done.
2018-10-20 00:24:53,951 INFO  [LocalJobRunner Map Task Executor #0] mapred.LocalJobRunner (LocalJobRunner.java:run(249)) - Finishing task: attempt_local908659401_0010_m_000000_0
2018-10-20 00:24:53,951 INFO  [Thread-209] mapred.LocalJobRunner (LocalJobRunner.java:runTasks(456)) - map task executor complete.
2018-10-20 00:24:53,953 INFO  [Thread-209] mapred.LocalJobRunner (LocalJobRunner.java:runTasks(448)) - Waiting for reduce tasks
2018-10-20 00:24:53,959 INFO  [pool-30-thread-1] mapred.LocalJobRunner (LocalJobRunner.java:run(302)) - Starting task: attempt_local908659401_0010_r_000000_0
2018-10-20 00:24:53,960 INFO  [pool-30-thread-1] mapred.Task (Task.java:initialize(587)) -  Using ResourceCalculatorProcessTree : [ ]
2018-10-20 00:24:53,960 INFO  [pool-30-thread-1] mapred.ReduceTask (ReduceTask.java:run(362)) - Using ShuffleConsumerPlugin: org.apache.hadoop.mapreduce.task.reduce.Shuffle@54b5ab1
2018-10-20 00:24:53,965 INFO  [pool-30-thread-1] reduce.MergeManagerImpl (MergeManagerImpl.java:<init>(196)) - MergerManager: memoryLimit=724461120, maxSingleShuffleLimit=181115280, mergeThreshold=478144352, ioSortFactor=10, memToMemMergeOutputsThreshold=10
2018-10-20 00:24:53,967 INFO  [EventFetcher for fetching Map Completion Events] reduce.EventFetcher (EventFetcher.java:run(61)) - attempt_local908659401_0010_r_000000_0 Thread started: EventFetcher for fetching Map Completion Events
2018-10-20 00:24:53,968 INFO  [localfetcher#10] reduce.LocalFetcher (LocalFetcher.java:copyMapOutput(141)) - localfetcher#10 about to shuffle output of map attempt_local908659401_0010_m_000000_0 decomp: 2 len: 6 to MEMORY
2018-10-20 00:24:53,969 INFO  [localfetcher#10] reduce.InMemoryMapOutput (InMemoryMapOutput.java:shuffle(100)) - Read 2 bytes from map-output for attempt_local908659401_0010_m_000000_0
2018-10-20 00:24:53,969 INFO  [localfetcher#10] reduce.MergeManagerImpl (MergeManagerImpl.java:closeInMemoryFile(314)) - closeInMemoryFile -> map-output of size: 2, inMemoryMapOutputs.size() -> 1, commitMemory -> 0, usedMemory ->2
2018-10-20 00:24:53,969 INFO  [EventFetcher for fetching Map Completion Events] reduce.EventFetcher (EventFetcher.java:run(76)) - EventFetcher is interrupted.. Returning
2018-10-20 00:24:53,969 INFO  [pool-30-thread-1] mapred.LocalJobRunner (LocalJobRunner.java:statusUpdate(591)) - 1 / 1 copied.
2018-10-20 00:24:53,969 INFO  [pool-30-thread-1] reduce.MergeManagerImpl (MergeManagerImpl.java:finalMerge(674)) - finalMerge called with 1 in-memory map-outputs and 0 on-disk map-outputs
2018-10-20 00:24:53,970 INFO  [pool-30-thread-1] mapred.Merger (Merger.java:merge(597)) - Merging 1 sorted segments
2018-10-20 00:24:53,970 INFO  [pool-30-thread-1] mapred.Merger (Merger.java:merge(696)) - Down to the last merge-pass, with 0 segments left of total size: 0 bytes
2018-10-20 00:24:53,970 INFO  [pool-30-thread-1] reduce.MergeManagerImpl (MergeManagerImpl.java:finalMerge(751)) - Merged 1 segments, 2 bytes to disk to satisfy reduce memory limit
2018-10-20 00:24:53,971 INFO  [pool-30-thread-1] reduce.MergeManagerImpl (MergeManagerImpl.java:finalMerge(781)) - Merging 1 files, 6 bytes from disk
2018-10-20 00:24:53,971 INFO  [pool-30-thread-1] reduce.MergeManagerImpl (MergeManagerImpl.java:finalMerge(796)) - Merging 0 segments, 0 bytes from memory into reduce
2018-10-20 00:24:53,971 INFO  [pool-30-thread-1] mapred.Merger (Merger.java:merge(597)) - Merging 1 sorted segments
2018-10-20 00:24:53,971 INFO  [pool-30-thread-1] mapred.Merger (Merger.java:merge(696)) - Down to the last merge-pass, with 0 segments left of total size: 0 bytes
2018-10-20 00:24:53,971 INFO  [pool-30-thread-1] mapred.LocalJobRunner (LocalJobRunner.java:statusUpdate(591)) - 1 / 1 copied.
2018-10-20 00:24:53,980 INFO  [pool-30-thread-1] mapred.Task (Task.java:done(1001)) - Task:attempt_local908659401_0010_r_000000_0 is done. And is in the process of committing
2018-10-20 00:24:53,981 INFO  [pool-30-thread-1] mapred.LocalJobRunner (LocalJobRunner.java:statusUpdate(591)) - 1 / 1 copied.
2018-10-20 00:24:53,981 INFO  [pool-30-thread-1] mapred.Task (Task.java:commit(1162)) - Task attempt_local908659401_0010_r_000000_0 is allowed to commit now
2018-10-20 00:24:53,982 INFO  [pool-30-thread-1] output.FileOutputCommitter (FileOutputCommitter.java:commitTask(439)) - Saved output of task 'attempt_local908659401_0010_r_000000_0' to file:/home/ptrivedi/project3/output/_temporary/0/task_local908659401_0010_r_000000
2018-10-20 00:24:53,983 INFO  [pool-30-thread-1] mapred.LocalJobRunner (LocalJobRunner.java:statusUpdate(591)) - reduce > reduce
2018-10-20 00:24:53,983 INFO  [pool-30-thread-1] mapred.Task (Task.java:sendDone(1121)) - Task 'attempt_local908659401_0010_r_000000_0' done.
2018-10-20 00:24:53,983 INFO  [pool-30-thread-1] mapred.LocalJobRunner (LocalJobRunner.java:run(325)) - Finishing task: attempt_local908659401_0010_r_000000_0
2018-10-20 00:24:53,983 INFO  [Thread-209] mapred.LocalJobRunner (LocalJobRunner.java:runTasks(456)) - reduce task executor complete.
2018-10-20 00:24:54,909 INFO  [main] mapreduce.Job (Job.java:monitorAndPrintJob(1366)) - Job job_local908659401_0010 running in uber mode : false
2018-10-20 00:24:54,909 INFO  [main] mapreduce.Job (Job.java:monitorAndPrintJob(1373)) -  map 100% reduce 100%
2018-10-20 00:24:54,909 INFO  [main] mapreduce.Job (Job.java:monitorAndPrintJob(1384)) - Job job_local908659401_0010 completed successfully
2018-10-20 00:24:54,920 INFO  [main] mapreduce.Job (Job.java:monitorAndPrintJob(1391)) - Counters: 33
	File System Counters
		FILE: Number of bytes read=185272
		FILE: Number of bytes written=5283836
		FILE: Number of read operations=0
		FILE: Number of large read operations=0
		FILE: Number of write operations=0
	Map-Reduce Framework
		Map input records=0
		Map output records=0
		Map output bytes=0
		Map output materialized bytes=6
		Input split bytes=122
		Combine input records=0
		Combine output records=0
		Reduce input groups=0
		Reduce shuffle bytes=6
		Reduce input records=0
		Reduce output records=0
		Spilled Records=0
		Shuffled Maps =1
		Failed Shuffles=0
		Merged Map outputs=1
		GC time elapsed (ms)=5
		CPU time spent (ms)=0
		Physical memory (bytes) snapshot=0
		Virtual memory (bytes) snapshot=0
		Total committed heap usage (bytes)=2069889024
	Shuffle Errors
		BAD_ID=0
		CONNECTION=0
		IO_ERROR=0
		WRONG_LENGTH=0
		WRONG_MAP=0
		WRONG_REDUCE=0
	File Input Format Counters 
		Bytes Read=79
	File Output Format Counters 
		Bytes Written=8
