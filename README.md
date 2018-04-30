
# WebSec-Week9 - Honeypot
  

Time spent: **8** hours spent in total


> Objective: Setup a MHN server, deploy Dionaea honeypot, intercept and analyze attacks.

  
## Pentesting Report


**Deployed Honeypots** : Dionaea

**Attacks**: 
![attacks](https://i.imgur.com/odbWseA.jpg)

**Issues encountered**: 
 - Although the honeypot has intercepted and logged over 5,000 attacks, no binary malware data has been captured. I tried googling around but most of the resources available are either outdated or extremely vague. The following demo shows a couple of attack launched using metasploit framework, both target vulnerabilities in SMB on port 445; I  used *reverse tcp* & *bind tcp* payloads but both attacks failed.
 
 ![metasploit](https://i.imgur.com/Lq5PauC.gif)

**Summary of the data collected**

- [x] Number of attacks:   5263

**Unresolved questions**

How to configure the sensor to capture malware payloads.

## Resources

  - [MHN docs](https://github.com/threatstream/mhn)
  

GIFs created with [Peek](https://github.com/phw/peek)
  

## License

  

    Copyright [2018] [drsh0x]
    
      
    
        Licensed under the Apache License, Version 2.0 (the "License");
        
        you may not use this file except in compliance with the License.
        
        You may obtain a copy of the License at
        
          
        
        http://www.apache.org/licenses/LICENSE-2.0
        
          
        
        Unless required by applicable law or agreed to in writing, software
        
        distributed under the License is distributed on an "AS IS" BASIS,
        
        WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
        
        See the License for the specific language governing permissions and
        
        limitations under the License.
