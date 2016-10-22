
BDConnection api
------------

    vector<string> arpScan();
    bool recv(char* buffer,);
    bool send(Host host, char* buffer);
    bool hostExist(string ip);
    string iosDetection(string ip);
    Host scanHost(string ip);
    vector<Host> scanHosts();
    bool scanPortSyn(string ip, int port);
    bool scanPortConnection(string ip, int port);
    bool scanPortUdp(string ip, int port);
    Ports scanPortsSyn(string ip, vector<int> ports);
    Ports scanPortsConnection(string ip, vector<int> ports);
    Ports scanPortsUdp(string ip, vector<int> ports);
    Ports scanPortsSyn(string ip, int portStart, int portStop);
    Ports scanPortsConnection(string ip, int portStart, int portStop);
    Ports scanPortsUdp(string ip, int portStart, int portStop);