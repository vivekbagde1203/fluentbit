# fluentbit

We will start studying fluentbit flow process:

Logging

   1. Timestamp records of an events or record.
   2. Application generates a message: record
   3. Writing message to log files

 ##########################################################
 #                         Log                            #
 #  Application-------------------------------> Log Files #
 #                                                        #
 ##########################################################

 What to Log inside the kubernetes cluster?

 1. Application Log
 2. Kubernetes Cluster Logs
     a. Kube-apiserver
     b. kube-scheduler
     c. ETCD
     d. kube-proxy
     e. kubelete
 
 Here we will Learn about Fluentbit and it's architecture

 ###########
 Fluent bit
 ###########

1. opensource and very Light weight
2. Written in C
3. Created with specific use case in mind.

Here we will study how fluentbit will forward all logs to splunk,stdout and elasticsearch

#########################################################################################
# Logs---------------------->fluentbit------------------->splunk/elasticsearch/stdout   #
#########################################################################################

<img width="605" alt="image" src="https://user-images.githubusercontent.com/116063043/219923212-218dad98-acdc-46d9-9760-04bdb159311a.png">


