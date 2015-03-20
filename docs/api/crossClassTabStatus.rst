.. _sendmail-api:

[API] Cross Class Tab relevant 
===============

.. http:post:: /class_readTabStatus?(long:groupId)

   Replies a comment to the post.

   :param groupId: post's unique id
   :type groupId: long
   :resheader Content-Type: json
   :status 400: when form parameters are missing



.. http:post:: /class_changeTabStatus?(long:groupId)&(boolean:status)

   :param groupId: post's unique id
   :type groupId: int
   :resheader Content-Type: json
   :status 400: when form parameters are missing