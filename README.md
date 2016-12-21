# Problem Statement: 

- Four services are running in different container’s -  2 instance each of S1 and S2 (S1 and S2 can be any service). 
- HAProxy to load balance in a round robin way between the two S1 service as well as two S2 services. 
- Also define HAProxy to do reverse proxy for S1 and S2.
- S1 accessable via http://test.com/s1
- S2 accessable via http://s2.test.com

Note: Please make use of Docker for all the services as well as HAProxy and share HAProxy config, Docker compose and Docker image files.
