NOTES
====================
Node name | Role 
mco-hub   | logical hub broker 
mco-b1    | spoke broker 

The file activemq-hub.xml would be used by the logical hub broker which does not have any defined networkConnectors.

The rest of the brokers would use the same activemq-spoke.xml.  Each node would have a uniquely name networkConnector.

The authorization/authentication maps have been stripped out.
