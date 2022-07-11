### Project Title - Deploy a high-availability web app using CloudFormation

network.yaml Resource List: 
- VPC
- InternetGateway
- InternetGatewayAttachment
- PublicSubnet1, PublicSubnet2
- PrivateSubnet1, PrivateSubnet2
- NatGateway1EIP, NatGateway2EIP
- NatGateway1, NatGateway2
- PublicRouteTable, DefaultPublicRoute
- PublicSubnet1RouteTableAssociation, PublicSubnet2RouteTableAssociation
- PrivateRouteTable1, DefaultPrivateRoute1
- PrivateSubnet1RouteTableAssociation
- PrivateRouteTable2, DefaultPrivateRoute2
- PrivateSubnet2RouteTableAssociation

Instructions
- to create the network settings, type "create.sh webnetwork network.yaml network-parameters.json"
- to create the server settings, type "create.sh webserver server.yaml server-parameters.json"

##Technology Used
yaml, json, shell

##Author
Tsai-Ting Wang

##Credits
Base Version is provided by Udacity

