# Improving Anomaly Detection in Audio by Learning How it Changes Over Time

This project examines a new way to detect anomalies in audio files via self-supervised
learning. The proposed method uses the fact that audio files contain information about a sequence of
events and thus learns the internal order of the audio to trace intrinsic properties of the normal
group. I show that the normal group has a unique time context that helps identify anomalies,
since the sequence of events in the anomaly observations does not match the order of the normal
group. Therefore, I suggest that combining existing methods together with the method of learning
from temporal context may improve the performance of finding anomalies in audio files.

The learning architecture of the normal group features includes three processes:


![image](https://user-images.githubusercontent.com/98801941/197716210-f68281e9-2940-4668-83bf-f0d32ab2ae4e.png)

1. Learning the direction of change of the normal group
2. Learning the rate of change of the normal group
3. Learning the content of the normal group.

In the phase of analyzing the findings, I show that the integration of new methods, which study how the normal group changes in the context of time, improves the detection of anomalies. Moreover, I show that at least part of the group of anomalies identified by them does not overlap with the anomalies identified by existing methods in the field, which indicates that the proposed methods identify a new characteristic that defines the normal group, which has not been characterized so far.

The full file can be found in this link:
https://drive.google.com/file/d/1Y_9uG4cV2nth7Jkjdl_bPg_n8_eKaTqb/view?usp=sharing
