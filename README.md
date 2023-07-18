# Chatlist_Feature
The chatlist feature utilizes the LRU (Least Recently Used) cache concept to manage chats efficiently. 
It employs a combination of a linked list and a hashmap data structure. 
New messages are added to the top of the linked list to maintain their priority. 
When a chat is deleted, it is removed from the linked list, causing lower chats to shift up. 
The hashmap keeps track of the chat's position in the linked list. 
This approach ensures quick access and deletion of chats, optimizing the use of memory and ensuring that the most recently accessed chats remain at the top for faster retrieval.
