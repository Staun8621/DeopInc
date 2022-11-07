In this section , I will implement traffic management in AZURE:

I did testing managing network traffic targeting Azure virtual machines in the hub and spoke network topology, 
which Contoso considers implementing in its Azure environment (instead of creating the mesh topology). 
This testing needs to include implementing connectivity between spokes by relying on user defined routes that 
force traffic to flow via the hub, as well as traffic distribution across virtual machines by using layer 4 
and layer 7 load balancers. For this purpose, I intend to use Azure Load Balancer (layer 4) and 
Azure Application Gateway (layer 7).

Objectives

Task 1: Provision the lab environment

Task 2: Configure the hub and spoke network topology

Task 3: Test transitivity of virtual network peering

Task 4: Configure routing in the hub and spoke topology

Task 5: Implement Azure Load Balancer

Task 6: Implement Azure Application Gateway