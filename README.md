# Aucta-Cognitio-Internship/Thesis

The need to store massive amounts of data creates the requirement for storage systems
capable of expanding their capacity accordingly. Among the open-source distributed
storage solutions available, Ceph notably stands out. Although Ceph is primarily
self-contained in caring for itself and recovering from failure scenarios, the data loss
problem is complex. It depends on many factors, including the OSDs distribution
across buckets and the various types of replication and fault domain policies utilized
in pools. In this complex, heterogeneous, and ever-changing scenario, it is challenging
for a Ceph system administrator to individuate the best Ceph deployment to mitigate
the risk of data loss a priori.
Furthermore, it is difficult to know how sensitive the data is to the network or bucket
failures. Equipping the administrator with a comprehensive view of which pools are
affected by data loss is crucial to provide a data loss service-oriented perspective.
This thesis aims to supply Ceph system administrators with a broad and service-
oriented view of a Ceph cluster during failures or in their anticipation. By equipping
them with reactive and proactive tools to gain knowledge on the data loss probability
of the pools, administrators can make informed decisions regarding the optimal Ceph
deployment strategy before failures. This approach helps mitigate the risk of data loss
in the pools.
The study has developed functions for incremental data loss probability assessment
and forecasting, which are integrated into a server component deployed within a Ceph
cluster. REST API and RPC clients have also been implemented to interact with
the server. The collective integration of these components forms a comprehensive
Service-Related Data Loss Evaluation System.

[READ Thesis.pdf for more]