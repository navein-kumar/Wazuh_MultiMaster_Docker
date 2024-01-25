--
wazuh-manager-master-01 --> direct expose 1514,1515 --> agent direct connection 
--
wazuh-manager-master-02  --> docker-compose change port 1517,1518 --> nginx --> forward proxy --> re-route the port to agent 
--
wazuh-manager-master-03 --> docker-compose change port 1517,1518 --> nginx --> forward proxy --> re-route the port to agent 
--
-- up to n master --
--
https://github.com/navein-kumar/Wazuh_Multi_Master_Docker
--
