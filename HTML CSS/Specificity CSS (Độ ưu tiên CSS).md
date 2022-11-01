https://www.w3schools.com/css/css_specificity.asp

<table>
  <tbody><tr>
    <th>Selector</th>
    <th>Specificity Value</th>
    <th>Calculation</th>
  </tr>
  <tr>
    <td>p</td>
    <td>1</td>
    <td>1</td>
  </tr>
  <tr>
    <td>p.test</td>
    <td>11</td>
    <td>1 + 10</td>
  </tr>
  <tr>
    <td>p#demo</td>
    <td>101</td>
    <td>1 + 100</td>
  </tr>
  <tr>
    <td>&lt;p style="color: pink;"&gt;</td>
    <td>1000</td>
    <td>1000</td>
  </tr>
  <tr>
    <td>#demo</td>
    <td>100</td>
    <td>100</td>
  </tr>
  <tr>
    <td>.test</td>
    <td>10</td>
    <td>10</td>
  </tr>
  <tr>
    <td>p.test1.test2</td>
    <td>21</td>
    <td>1 + 10 + 10</td>
  </tr>
  <tr>
    <td>#navbar p#demo</td>
    <td>201</td>
    <td>100 + 1 + 100</td>
  </tr>
  <tr>
    <td>*</td>
    <td>0</td>
    <td>0 (the universal selector is ignored)</td>
  </tr>
  </tbody></table>

# [[Inhentance (Sự thừa kế)]]
- Tham khảo