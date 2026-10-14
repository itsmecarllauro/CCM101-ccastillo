# Mission Reflection

## 1. How does a host based firewall protect a server even if the physical network perimeter is breached?

A host based firewall protects a server by controlling incoming and outgoing traffic directly on the server. Even if an attacker gets past the network firewall, the host based firewall can still block unwanted connections and allow only the services that are needed. This gives the server another layer of security.

## 2. Why is managing open ports critical to reducing a server's attack surface?

Managing open ports is important because every open port can be a possible way for attackers to access the server. If unnecessary ports are left open, attackers may find ways to exploit the services running on them. By allowing only the ports needed, such as SSH and port 8080, I can help reduce the server's attack surface.

## 3. Why is it dangerous to leave a database port, like 3306 for MySQL, open to the public internet?

Leaving port 3306 open to the public internet is dangerous because attackers may try to connect to the database and guess passwords or exploit security weaknesses. They could access, steal, or damage sensitive information if the database is not properly protected. I learned that database access should be limited to trusted systems that need it.

## 4. How did this mission change your view of how easily a server can be compromised?

This mission changed my view because I realized that a server can become vulnerable because of simple mistakes in its security settings. Before this activity, I did not fully understand the importance of configuring a firewall and checking open ports. Now, I know that regular security checks and proper firewall rules are important for protecting a server.

## 5. How does your GitHub portfolio look with eight completed missions?

Having eight completed missions in my GitHub portfolio makes me feel proud because I can see my progress in learning cloud computing. Each activity helped me gain new knowledge and practice different technical skills. My portfolio also shows the work I have completed and the skills I have developed. I know I still have more to learn, but these missions motivate me to keep improving my cloud computing and security skills.
