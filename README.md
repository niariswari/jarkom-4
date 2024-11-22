## CIDR

### Tree

- Tree image

  ![TREE-CIDR](https://github.com/user-attachments/assets/27e9514a-d986-464a-a1e4-7e79f3d78087)


- IP distribution table

  ![TABLE-CIDR](https://github.com/user-attachments/assets/14c41443-b0cb-4e30-b90b-3ec7b62594eb)


### Subnet Merging Iteration

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

  ![{6C2C39E3-FA79-4219-8353-5DEE12719AEE}](https://github.com/user-attachments/assets/084ebf42-1195-48c4-b70f-cc3c3956837b)

- Acqua:

  ```

  ```

- Aiwass:

  ```

  ```

- Aleister:

  ```

  ```

- Mathers:

  ```

  ```

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

  ```

  ```

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

  ```

  ```

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

  ```

  ```

- Othinus:

  ```

  ```

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

  ```

  ```

- Fuze:

  ```

  ```

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

  ```

  ```

- MentalOut:

  ```

  ```

- DarkMatter:

  ```

  ```

- Noukan:

  ```

  ```


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
  ip route 10.25.64.0 255.255.254.0 10.25.68.2 
  ip route 10.25.66.0 255.255.255.128 10.25.68.2 
  ip route 10.25.80.128 255.255.255.224 10.25.84.2 
  ip route 10.25.80.0 255.255.255.128 10.25.84.2 
  ip route 10.25.82.0 255.255.255.252 10.25.84.2 
  ip route 10.25.36.0 255.255.255.240 10.25.40.2 
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

  

- Client - Server

  

- Client - Router

  

- Server - Server

  

- Server - Router

  

- Router - Router

  
