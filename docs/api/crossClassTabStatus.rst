.. _sendmail-api:

[API] Cross Class Tab relevant 
===============

.. http:post:: /class_readTabStatus?(long:groupId)

   Replies a comment to the post.

   :param groupId: group id
   :type groupId: long
   :resheader Content-Type: json
   :status 400: when parameters are missing



.. http:post:: /class_changeTabStatus?(long:groupId)&(boolean:status)

   :param groupId: group id
   :type groupId: long
   :param status: true or false 
   :type status: boolean
   :resheader Content-Type: json
   :status 400: when parameters are missing