# ECDHCurves25519and448

Goal of this project was to implement an ECDH key exchange algorithm in order to get a shared key that can be used for message encryption. We also used two of the most popular curves - 448 & 25519 and compared their performance. Backbone of our project was [RFC7748](https://datatracker.ietf.org/doc/html/rfc7748 "https://datatracker.ietf.org/doc/html/rfc7748").

Below the curves were plotted next to each other, respectively ECDH448 and ECDH25519.

![image](https://user-images.githubusercontent.com/45394303/132241907-093076e4-d6bb-45fb-abfb-86182feed56b.png)
![image](https://user-images.githubusercontent.com/45394303/132241827-16ae30b2-c46c-4b41-a595-9893f070302b.png)

We have also tested the performance of each curve and the results weren't surprinsing since ECDH448 sometimes can be treated as overkill.

![image](https://user-images.githubusercontent.com/45394303/132241673-7a387d53-4800-464e-a5bf-a8fed043a075.png)


## Contributors
<table>
  <tr>
  <td align="cefix fixanter">
    <a href="https://github.com/pasonjakub">
      <img src="https://avatars.githubusercontent.com/u/45394303?s=460&u=7d8417314ae8a7da4f41697917a3e204bb39dd05&v=4" width="100px;" alt=""/>
      <br />
      <sub>
        <b>Jakub Pasoń</b>
      </sub>
    </a>
    <br />
  </td>
  <td align="cefix fixanter">
    <a href="https://github.com/HubixD">
      <img src="https://avatars.githubusercontent.com/u/45371697?s=460&v=4" width="100px;" alt=""/>
      <br />
      <sub>
        <b>Hubert Hanusiak</b>
      </sub>
    </a>
    <br />
  </td>
  <td align="cefix fixanter">
    <a href="https://github.com/WiesQ">
      <img src="https://avatars.githubusercontent.com/u/45373270?v=4" width="100px;" alt=""/>
      <br />
      <sub>
        <b>Seweryn Dumania</b>
      </sub>
    </a>
    <br />
  </td>
  <td align="cefix fixanter">
    <a href="https://github.com/any-sliv">
      <img src="https://avatars.githubusercontent.com/u/36036271?v=4" width="100px;" alt=""/>
      <br />
      <sub>
        <b>Maciej Śliwiński</b>
      </sub>
    </a>
    <br />
  </td>
 </tr>
</table>
