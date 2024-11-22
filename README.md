## Routing

- Routing table

  ![{F3ADE6A5-6F64-448F-BBAA-116467A7CE23}](https://github.com/user-attachments/assets/9a6e5b80-79e4-4e1c-a476-49b138fd8db0)


- Route visualization in topology

  ![A1](https://github.com/user-attachments/assets/1a34b671-1248-4131-b9ba-3ef6b0828492)


<br>

## CIDR

### Tree

- Tree image

  ![TREE-CIDR](https://github.com/user-attachments/assets/27e9514a-d986-464a-a1e4-7e79f3d78087)


- IP distribution table

  ![TABLE-CIDR](https://github.com/user-attachments/assets/14c41443-b0cb-4e30-b90b-3ec7b62594eb)


### Subnet Merging Iteration

![IMG_8505](https://github.com/user-attachments/assets/b6a34a91-f568-4ea5-b15f-d3fa8cad6358)

- Iteration 1

  ![MERGE-B](https://github.com/user-attachments/assets/378c9d5a-66f4-4464-bdbb-cefbdcc2db6f)


- Iteration 2

  ![MERGE-C](https://github.com/user-attachments/assets/6a24edc9-0c2d-44aa-a242-c4c05d9e3fc1)


- Iteration 3

  ![MERGE-D](https://github.com/user-attachments/assets/1affce82-0add-41f2-8c98-f0256110f489)


- Iteration 4

  ![MERGE-E](https://github.com/user-attachments/assets/4176fa7a-47f2-47d1-ac0e-76e6fda0e653)


- Iteration 5

  ![MERGE-F](https://github.com/user-attachments/assets/3071c648-d2d1-4271-94f6-f8e1f9b7ded8)


- Iteration 6

  ![MERGE-G](https://github.com/user-attachments/assets/7e976d48-46d0-46f1-822b-af75d9a8fe32)


- Iteration G

  ![MERGE-H](https://github.com/user-attachments/assets/4b4336d8-3f7d-4396-94a7-11132bfcc556)


### Subnetting (If you use CPT)

Configuration to every router, client, and server for subnetting.

- Kamachi:

  ```
  interface FastEthernet0/1
   ip address 10.25.76.1 255.255.255.252
   duplex auto
   speed auto
  !
  interface Ethernet0/0/0
   ip address 10.25.68.1 255.255.255.252
   duplex auto
   speed auto
  !
  interface Ethernet0/1/0
   ip address 10.25.84.1 255.255.255.252
   duplex auto
   speed auto
  !
  interface FastEthernet1/0
   ip address 10.25.16.1 255.255.255.252
   duplex auto
   speed auto
  !
  interface FastEthernet1/1
   ip address 10.25.40.1 255.255.255.252
   duplex auto
   speed auto
  ```

- Fiamma:

  ```
  interface FastEthernet0/0
   ip address 10.25.76.2 255.255.255.252
   duplex auto
   speed auto
  !
  interface FastEthernet0/1
   ip address 10.25.74.1 255.255.254.0
   duplex auto
   speed auto
  !
  ```

- GoldenDawn:

  ```
  interface FastEthernet0/0
   ip address 10.25.16.2 255.255.255.252
   duplex auto
   speed auto
  !
  interface FastEthernet0/1
   ip address 10.25.0.1 255.255.248.0
   duplex auto
   speed auto
  !
  interface FastEthernet1/0
   ip address 10.25.8.1 255.255.255.252
   duplex auto
   speed auto
  !
  ```

- Necessarius:

  ```
  interface FastEthernet0/0
   ip address 10.25.40.2 255.255.255.252
   duplex auto
   speed auto
  !
  interface FastEthernet0/1
   ip address 10.25.36.65 255.255.255.252
   duplex auto
   speed auto
  !
  interface FastEthernet1/0
   ip address 10.25.34.1 255.255.255.252
   duplex auto
   speed auto
  !
  ```

- Alice:

  ```
  interface FastEthernet0/0
   ip address 10.25.68.2 255.255.255.252
   duplex auto
   speed auto
  !
  interface FastEthernet0/1
   ip address 10.25.64.1 255.255.254.0
   duplex auto
   speed auto
  !
  ```

- Kihara:

  ```
  interface FastEthernet0/0
   ip address 10.25.84.2 255.255.255.252
   duplex auto
   speed auto
  !
  interface FastEthernet0/1
   ip address 10.25.81.1 255.255.255.252
   duplex auto
   speed auto
  !
  interface FastEthernet1/0
   ip address 10.25.82.1 255.255.255.252
   duplex auto
   speed auto
  !
  ```

- Vento:

  ```
  interface FastEthernet0/0
   ip address 10.25.74.3 255.255.254.0
   duplex auto
   speed auto
  !
  interface FastEthernet0/1
   ip address 10.25.72.1 255.255.255.224
   duplex auto
   speed auto
  !
  ```

- Terra:

  ![{A38D49DB-1E25-4F99-8CF1-56A039EF36EA}](https://github.com/user-attachments/assets/1bd6851f-0a98-441b-903e-6938914f35a5)


- Acqua:

  ![{D843A7C4-9A2E-4335-A5B9-E7A3706A823F}](https://github.com/user-attachments/assets/3ceeaa77-38df-4ce5-85af-6e188f00ac57)


- Aiwass:

  ![{38022B92-0021-41CC-98DE-A01AA622E403}](https://github.com/user-attachments/assets/99c86570-1e80-4200-b7a9-d42e2480d1b8)


- Aleister:

  ![{9BDC3750-10DB-4D84-8C15-933BF687A091}](https://github.com/user-attachments/assets/ec2b30d7-9748-4081-8882-f28afad20ca1)


- Mathers:

  ![{932283A8-028C-4E07-A6CE-E994566EB973}](https://github.com/user-attachments/assets/230ee07e-0ded-49eb-ba23-8bc36135cd60)


- Coronzon:

  ```
  interface FastEthernet0/0
   ip address 10.25.36.66 255.255.255.252
   duplex auto
   speed auto
  !
  interface FastEthernet0/1
   ip address 10.25.36.33 255.255.255.252
   duplex auto
   speed auto
  !
  interface FastEthernet1/0
   ip address 10.25.36.17 255.255.255.252
   duplex auto
   speed auto
  !
  ```

- Elizard:

  ![{E0D27A95-EA38-4E00-9F2C-B07D42EBDB3C}](https://github.com/user-attachments/assets/8224c63b-3c44-44bb-a7cb-189d92ea4da3)


- Index:

  ```
  interface FastEthernet0/0
   ip address 10.25.36.18 255.255.255.252
   duplex auto
   speed auto
  !
  interface FastEthernet0/1
   ip address 10.25.36.1 255.255.255.240
   duplex auto
   speed auto
  !
  ```

- Magnus:

  ![{B90A1500-9399-48C4-A6E4-2747F14DBC7C}](https://github.com/user-attachments/assets/a4467beb-b4b2-4b99-b1b1-cf518b7e8134)


- Gremlin:

  ```
  interface FastEthernet0/0
   ip address 10.25.34.2 255.255.255.252
   duplex auto
   speed auto
  !
  interface FastEthernet0/1
   ip address 10.25.32.1 255.255.254.0
   duplex auto
   speed auto
  !
  ```

- Thor:

  ![{1A9C6307-4960-4D52-9A71-87E2652E41C7}](https://github.com/user-attachments/assets/2422165f-e934-45de-ab44-a3f7d1c1322a)


- Othinus:

  ![{64645FFC-332D-41F0-BC21-F4D64FF4F15E}](https://github.com/user-attachments/assets/492a0a08-03b2-4b90-b9b2-5d04ae84d5a2)


- LastOrder:

  ```
  interface FastEthernet0/0
   ip address 10.25.65.254 255.255.254.0
   duplex auto
   speed auto
  !
  interface FastEthernet0/1
   ip address 10.25.66.1 255.255.255.128
   duplex auto
   speed auto
  !
  ```

- Leivinia:

  ![{6FEDF7A9-B88A-45E4-B237-58FA27C25BD7}](https://github.com/user-attachments/assets/87fe0ead-52e6-493d-bdc4-c4b00b4cfba1)


- Fuze:

  ![{DECE27A6-A2B9-4A0B-8A89-8A6052A442C3}](https://github.com/user-attachments/assets/f138b322-8464-45e4-9052-f20d4037aa03)


- Accel:

  ```
  interface FastEthernet0/0
   ip address 10.25.81.2 255.255.255.252
   duplex auto
   speed auto
  !
  interface FastEthernet0/1
   ip address 10.25.80.1 255.255.255.128
   duplex auto
   speed auto
  !
  ```

- Railgun:

  ```
  interface FastEthernet0/0
   ip address 10.25.80.111 255.255.255.128
   duplex auto
   speed auto
  !
  interface FastEthernet0/1
   ip address 10.25.80.129 255.255.255.224
   duplex auto
   speed auto
  !
  ```

- MeltDowner:

  ![{C5A0F8F1-4583-468D-BECD-784D99A93279}](https://github.com/user-attachments/assets/f35b59d8-8baa-4eed-bd7d-5d8c327490da)


- MentalOut:

  ![{4C1BA933-3D6E-4BB9-A0B4-57C23DE0EAC1}](https://github.com/user-attachments/assets/1a442b69-c616-462b-8373-58206102dc5a)


- DarkMatter:

  ![{272CA1FC-BDAD-4F03-B833-3BBB46D4AF89}](https://github.com/user-attachments/assets/5e9b10c1-3bf7-4cba-8c5c-aa58ee96e685)


- Noukan:

  ![{C0D2B0C8-C036-4C55-88D1-F425BFAF36B0}](https://github.com/user-attachments/assets/03e0534f-fe8b-42fe-b1df-7375375e2727)



### Routing

Configuration to every router for routing.

- Kamachi:

  ```
  ip route 10.25.74.0 255.255.254.0 10.25.76.2 
  ip route 10.25.72.0 255.255.255.224 10.25.76.2 
  ip route 10.25.8.0 255.255.255.252 10.25.16.2 
  ip route 10.25.0.0 255.255.248.0 10.25.16.2 
  ip route 10.25.36.32 255.255.255.252 10.25.40.2 
  ip route 10.25.36.16 255.255.255.252 10.25.40.2 
  ip route 10.25.32.0 255.255.254.0 10.25.40.2
  ip route 10.25.36.0 255.255.255.240 10.25.40.2
  ip route 10.25.34.0 255.255.255.240 10.25.40.2
  ip route 10.25.36.64 255.255.255.240 10.25.40.2
  ip route 10.25.64.0 255.255.254.0 10.25.68.2 
  ip route 10.25.66.0 255.255.255.128 10.25.68.2 
  ip route 10.25.80.128 255.255.255.224 10.25.84.2 
  ip route 10.25.80.0 255.255.255.128 10.25.84.2 
  ip route 10.25.81.0 255.255.255.128 10.25.84.2 
  ip route 10.25.82.0 255.255.255.252 10.25.84.2 
  ```

- Fiamma:

  ```
  ip route 0.0.0.0 0.0.0.0 10.25.76.1 
  ip route 10.25.72.0 255.255.255.224 10.25.74.3
  ```

- GoldenDawn:

  ```
  ip route 0.0.0.0 0.0.0.0 10.25.16.1 
  ```

- Necessarius:

  ```
  ip route 10.25.36.32 255.255.255.252 10.25.36.66 
  ip route 10.25.32.0 255.255.254.0 10.25.34.2 
  ip route 10.25.36.0 255.255.255.240 10.25.36.66
  ip route 10.25.36.16 255.255.255.240 10.25.36.66
  ip route 0.0.0.0 0.0.0.0 10.25.40.1 
  ```

- Alice:

  ```
  ip route 10.25.66.0 255.255.255.128 10.25.65.254 
  ip route 0.0.0.0 0.0.0.0 10.25.68.1 
  ```

- Kihara:

  ```
  ip route 10.25.80.0 255.255.255.128 10.25.81.2 
  ip route 10.25.80.128 255.255.255.224 10.25.81.2 
  ip route 0.0.0.0 0.0.0.0 10.25.84.1
  ```

- Vento:

  ```
  ip route 0.0.0.0 0.0.0.0 10.25.74.1 
  ```

- Coronzon:

  ```
  ip route 10.25.36.0 255.255.255.240 10.25.36.18 
  ip route 0.0.0.0 0.0.0.0 10.25.36.65 
  ```

- Index:

  ```
  ip route 0.0.0.0 0.0.0.0 10.25.36.17 
  ```

- Gremlin:

  ```
  ip route 0.0.0.0 0.0.0.0 10.25.34.1 
  ```

- LastOrder:

  ```
  ip route 0.0.0.0 0.0.0.0 10.25.64.1 
  ```

- Accel:

  ```
  ip route 10.25.80.128 255.255.255.224 10.25.80.111 
  ip route 0.0.0.0 0.0.0.0 10.25.81.1 
  ```

- Railgun:

  ```
  ip route 0.0.0.0 0.0.0.0 10.25.80.1 
  ```

### Testing

- Client - client

  ![{A1BBF769-F172-4311-A70E-0DE476C8EA89}](https://github.com/user-attachments/assets/49f12d86-47bf-4f19-8481-8a10711a9dd7)


- Client - Server

  ![{17D639B7-F2D1-4452-B954-788C318F8B4B}](https://github.com/user-attachments/assets/d28322cc-b53e-4de5-b78a-9eca0c39ce94)


- Client - Router

  ![{08BF771C-AECF-43A6-BCB9-1D641A0B2079}](https://github.com/user-attachments/assets/a62a4b58-a551-418c-87e0-242b2e1b540b)


- Server - Server

  ![{7EFA7A89-36C2-4855-94A1-4F02D241704E}](https://github.com/user-attachments/assets/4af5cfae-1f0c-4b3c-bc5d-66b8072fdb24)


- Server - Router

  ![{A5088AA0-8D17-40E9-8651-A6AF8025B733}](https://github.com/user-attachments/assets/d8fe2186-b51f-46da-a31f-e168f82c3ea1)


- Router - Router

  ![{4B673F83-3D42-4990-AA36-9098D013D114}](https://github.com/user-attachments/assets/bfb940a5-fbcf-4e7f-93e6-0ee7a3b97b2d)

