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

########################################################################
# k8s                                                    splunk        #
# prometheus               fluentbit                     datadog       #
# linux                                                  cloudwatch    #
# syslog                                                 elasticsearch #
# firewall                                               opensearch    #
########################################################################

