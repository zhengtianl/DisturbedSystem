# DisturbedSystem
# Lecture 2
sockets  
Briefly discuss three aspects of the Socket interface.  
Ans:  
1. Bound to local port Socket address = IP + Port number
2. Acts as programming interface to application code and transport layer
3. Socket handle is mostly like file handle
4. Each socket is associated with a protocol(TCP or UDP)

UDP three problems that UDP will cause:
1. Data Corruption
2. Omission failuers(No guaranteed delivery)
3. Order

Q3. Briefly explain aspects of TCP that address issues not addressed by UDP.
<br>1. Connection oriented: The communicating processes establish a connection before communicating.The connection involves a connect request from the client to the server followed by an acceptrequest from the server to the client.
</br>
<br>2.Message sizes: There is no limit on data size applications can use.
</br>
<br>3. Lost messages: TCP uses an acknowledgment scheme unlike UDP. If acknowledgments are not received the messages are retransmitted.
</br>
<br>4. Flow control: TCP protocol attempts to match the speed of the process that reads the message and writes to the stream.
</br>
<br>5.Message duplication or ordering: Message identifiers are associated with IP packets to enable the recipient to detect and reject duplicates and reorder messages in case messages arrive out of order
</br>




