The OCPP 1.6J communication protocol between the charging station and the server is not as complicated as it can be described in the instructions and official documentation. For several years of work, I realized one important thing, no matter what programming language you implement, the most important thing is to understand that the server should respond to charging stations. In this guide, I describe sample responses to commands in JSON format.

The manual describes the basic methods of working with the OCPP 1.6J protocol. If you are developing new code, the number of methods will be enough to develop a stable release version.

My release is developed for
PHP programming language using the WebSocket Ratchet library

If you have any questions, write to me, I will try to help with the implementation
https://www.instagram.com/gennadiy.gnezdilov/
