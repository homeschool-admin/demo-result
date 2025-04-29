<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Class 9-A Annual Exam Result</title>
  <style>
    body { 
      font-family: 'Arial', sans-serif; 
      background: #f0f8ff; /* Light Background Color */
      padding: 20px; 
      color: #333;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
    }

    .container {
      text-align: center;
      width: 100%;
      max-width: 800px;
      background-color: #fff;
      padding: 30px;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
    }

    h1 { 
      color: #1E90FF; /* Dark Sky Blue */
      font-size: 36px; 
      text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3);
      margin-top: 0;
    }

    h2.school-name { 
      font-size: 24px; 
      color: #1E90FF; 
      margin-top: -10px; 
    }

    input {
      padding: 12px 20px;
      width: 250px;
      font-size: 18px;
      margin-bottom: 20px;
      border: 2px solid #1E90FF;
      border-radius: 10px;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
      transition: border 0.3s ease;
    }

    input:focus {
      border: 2px solid #ff6600;
      outline: none;
    }

    button {
      padding: 12px 20px;
      font-size: 18px;
      background-color: #1E90FF;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }

    button:hover {
      background-color: #ff6600;
    }

    #result {
      margin-top: 40px;
      background-color: #fff;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 6px 15px rgba(0, 0, 0, 0.1);
      width: 100%;
    }

    table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 20px;
    }

    th, td {
      padding: 12px;
      text-align: center;
      border: 1px solid #ddd;
      font-size: 18px;
    }

    th {
      background-color: #1E90FF;
      color: white;
    }

    tr:nth-child(even) {
      background-color: #f2f2f2;
    }

    tr:hover {
      background-color: #f1f1f1;
    }

    .no-result {
      text-align: center;
      color: #ff6600;
      font-size: 18px;
      font-weight: bold;
    }
  </style>
</head>
<body>

  <div class="container">
    <h1>Shri Dakshinamurti Vinay Mandir - Bhavnagar</h1>
    <h2 class="school-name">Result of Annual Exam 2024-25 - Class 9-A</h2>

    <input type="text" id="seatInput" placeholder="Enter Seat Number" />
    <button onclick="searchResult()">Search</button>

    <div id="result"></div>
  </div>

  <script>
    const students = {
      "9101": { name: "અંજલીબેન ભગતભાઈ બરૈયા", gujarati: 88, english: 86, hindi: 83, sanskrit: 97, maths: 94, science: 89, social: 99, total: 636, percentage: 90.86 },
      "9102": { name: "ધારાબેન ધર્મેશભાઈ આલ", gujarati: 76, english: 65, hindi: 78, sanskrit: 89, maths: 86, science: 82, social: 97, total: 573, percentage: 81.86 },
      "9103": { name: "ફોરમ રાજેન્દ્રભાઈ મહેતા", gujarati: 84, english: 88, hindi: 90, sanskrit: 93, maths: 98, science: 90, social: 100, total: 643, percentage: 91.86 },
      "9104": { name: "કોમલ પ્રવિણભાઈ રાઠોડ", gujarati: 71, english: 75, hindi: 65, sanskrit: 88, maths: 71, science: 64, social: 87, total: 521, percentage: 74.43 },
      "9105": { name: "ક્રિષ્ના લાલજીભાઈ સિંધવ", gujarati: 77, english: 71, hindi: 69, sanskrit: 70, maths: 87, science: 70, social: 92, total: 536, percentage: 76.57 },
      "9106": { name: "નમ્રતાબેન જેન્તીભાઈ બાંભણીયા", gujarati: 79, english: 77, hindi: 76, sanskrit: 86, maths: 97, science: 75, social: 96, total: 586, percentage: 83.71 },
      "9107": { name: "નિશા સુરેશભાઈ કરખડિયા", gujarati: 78, english: 66, hindi: 75, sanskrit: 88, maths: 79, science: 66, social: 93, total: 545, percentage: 77.86},
      "9108": { name: "પ્રાચી હિતેશભાઈ જાદવ", gujarati: 74, english: 72, hindi: 74, sanskrit: 93, maths: 92, science: 67, social: 92, total: 564, percentage: 80.57},
      "9109": { name: "પ્રકૃતિ રાજેશભાઈ સોરઠિયા", gujarati: 75, english: 86, hindi: 73, sanskrit: 90, maths: 68, science: 71, social: 95, total: 558, percentage: 79.71},
      "9110": { name: "રુચા ઓમપ્રકાશભાઈ ત્રિવેદી", gujarati: 59, english: 95, hindi: 57, sanskrit: 85, maths: 87, science: 57, social: 96, total: 536, percentage: 76.57},
      "9111": { name: "રૂશિતાબેન બળવંતભાઈ મોરી", gujarati: 68, english: 71, hindi: 77, sanskrit: 79, maths: 63, science: 65, social: 89, total: 512, percentage: 73.14},
      "9112": { name: "સાક્ષી બાબુભાઈ મકવાણા", gujarati: 72, english: 75, hindi: 63, sanskrit: 62, maths: 34, science: 50, social: 89, total: 445, percentage: 63.57},
      "9113": { name: "સાક્ષી રાજુભાઈ રાઠોડ", gujarati: 71, english: 75, hindi: 67, sanskrit: 66, maths: 61, science: 48, social: 86, total: 474, percentage: 67.71},
      "9114": { name: "સર્વાંગીબા કરણભાઈ જાળિયા", gujarati: 62, english: 45, hindi: 59, sanskrit: 61, maths: 50, science: 43, social: 78, total: 398, percentage: 56.86},
      "9115": { name: "શિવાંગી સુનિલભાઈ ચુડાસમા", gujarati: 76, english: 77, hindi: 79, sanskrit: 94, maths: 96, science: 69, social: 83, total: 574, percentage: 82.00},
      "9116": { name: "અભય કૃષ્ણકુમાર વિંઝુડા", gujarati: 61, english: 59, hindi: 51, sanskrit: 63, maths: 49, science: 41, social: 79, total: 403, percentage: 57.57},
      "9117": { name: "અભિરાજ કિરીટભાઈ સોંડાગર", gujarati: 59, english: 44, hindi: 59, sanskrit: 60, maths: 38, science: 37, social: 61, total: 358, percentage: 51.14},
      "9118": { name: "અબ્રાર શબ્બીરભાઈ ઘોઘારી", gujarati: 70, english: 87, hindi: 77, sanskrit: 90, maths: 86, science: 75, social: 95, total: 580, percentage: 82.86},
      "9119": { name: "અમનકુમાર ભગતભાઈ બરૈયા", gujarati: 73, english: 79, hindi: 76, sanskrit: 87, maths: 88, science: 77, social: 91, total: 571, percentage: 81.57},
      "9120": { name: "આશિક સુરેશભાઈ વેગડ", gujarati: 67, english: 67, hindi: 67, sanskrit: 81, maths: 71, science: 66, social: 81, total: 500, percentage: 71.43},
      "9121": { name: "ભાવેશ પરશોતમભાઈ પરમાર", gujarati: 50, english: 62, hindi: 50, sanskrit: 80, maths: 71, science: 58, social: 72, total: 443, percentage: 63.29},
      "9122": { name: "ભવ્ય સોમેશ્વરભાઈ ભોઈ", gujarati: 70, english: 77, hindi: 72, sanskrit: 75, maths: 96, science: 78, social: 90, total: 558, percentage: 79.71},
      "9123": { name: "દક્ષ સુનિલભાઈ યાદવ", gujarati: 57, english: 60, hindi: 53, sanskrit: 67, maths: 54, science: 56, social: 68, total: 415, percentage: 59.29},
      "9124": { name: "દીપ દિનેશભાઈ બોરીચા", gujarati: 57, english: 66, hindi: 60, sanskrit: 69, maths: 75, science: 45, social: 88, total: 460, percentage: 65.71},
      "9125": { name: "દેવરાજ જીવાભાઈ વાઘેલા", gujarati: 53, english: 54, hindi: 48, sanskrit: 55, maths: 81, science: 52, social: 69, total: 412, percentage: 58.86},
      "9126": { name: "ધર્મરાજસિંહ નરેન્દ્રસિંહ વાજા", gujarati: 48, english: 60, hindi: 47, sanskrit: 59, maths: 42, science: 55, social: 79, total: 390, percentage: 55.71},
      "9127": { name: "ધર્મરાજસિંહ રાજેન્દ્રસિંહ ગોહિલ", gujarati: 55, english: 84, hindi: 60, sanskrit: 76, maths: 92, science: 79, social: 70, total: 516, percentage: 73.71},
      "9128": { name: "ધાર્મિક પ્રવિણભાઈ બરૈયા", gujarati: 64, english: 75, hindi: 64, sanskrit: 76, maths: 77, science: 70, social: 80, total: 506, percentage: 72.29},
      "9129": { name: "ધ્રુવ લાલાભાઈ ડાભી", gujarati: 23, english: 17, hindi: 20, sanskrit: 17, maths: 16, science: 18, social: 23, total: 134, percentage: 19.14},
      "9130": { name: "ધ્રુવગીરી ગૌરંગગીરી ગૌસ્વામી", gujarati: 58, english: 59, hindi: 56, sanskrit: 69, maths: 57, science: 43, social: 66, total: 408, percentage: 58.29},
      "9131": { name: "ગૌરવ ગોવિંદભાઈ ટેભાણી", gujarati: 58, english: 73, hindi: 71, sanskrit: 77, maths: 58, science: 60, social: 86, total: 483, percentage: 69.00},
      "9132": { name: "ગૌતમ કિશોરભાઈ સોલંકી", gujarati: 67, english: 81, hindi: 71, sanskrit: 85, maths: 87, science: 73, social: 96, total: 560, percentage: 80.00},
      "9133": { name: "હેમાંગ હરેશભાઈ ચૌહાણ", gujarati: 73, english: 80, hindi: 80, sanskrit: 91, maths: 98, science: 89, social: 99, total: 610, percentage: 87.14},
      "9134": { name: "જૈનિલ કેતનકુમાર ચૌહાણ", gujarati: 41, english: 44, hindi: 42, sanskrit: 53, maths: 25, science: 36, social: 58, total: 299, percentage: 42.71},
      "9135": { name: "જયંત લાલજીભાઈ ભલગામિયા", gujarati: 54, english: 82, hindi: 58, sanskrit: 70, maths: 46, science: 56, social: 79, total: 445, percentage: 63.57},
      "9136": { name: "જયેશ સંજયભાઈ રાઠોડ", gujarati: 70, english: 71, hindi: 70, sanskrit: 80, maths: 89, science: 68, social: 95, total: 543, percentage: 77.57},
      "9137": { name: "જયપાલસિંહ અજીતસિંહ સિંધા", gujarati: 54, english: 67, hindi: 49, sanskrit: 60, maths: 51, science: 36, social: 68, total: 385, percentage: 55.00},
      "9138": { name: "જૈમીલ મહેશભાઈ વાવડિયા", gujarati: 64, english: 84, hindi: 56, sanskrit: 86, maths: 92, science: 64, social: 92, total: 538, percentage: 76.86},
      "9139": { name: "જીગર મહેશભાઈ ભૂતૈયા", gujarati: 59, english: 80, hindi: 56, sanskrit: 64, maths: 84, science: 59, social: 85, total: 487, percentage: 69.57},
      "9140": { name: "કરણસિંહ યુવરાજસિંહ ચૌહાણ", gujarati: 54, english: 61, hindi: 52, sanskrit: 53, maths: 70, science: 52, social: 82, total: 424, percentage: 60.57},
      "9141": { name: "કાર્તિક રાજેશભાઈ રાઠોડ", gujarati: 50, english: 55, hindi: 57, sanskrit: 65, maths: 65, science: 64, social: 69, total: 425, percentage: 60.71},
      "9142": { name: "કાવ્ય શૈલેષભાઈ ડબગર", gujarati: 55, english: 69, hindi: 57, sanskrit: 76, maths: 95, science: 54, social: 86, total: 492, percentage: 70.29},
      "9143": { name: "કેનિલ અજયભાઈ મકવાણા", gujarati: 39, english: 59, hindi: 39, sanskrit: 54, maths: 57, science: 42, social: 70, total: 360, percentage: 51.43},
      "9144": { name: "કૃષ્ણકુમારસિંહ ઇશ્વરભાઇ પઢિયાર", gujarati: 41, english: 62, hindi: 41, sanskrit: 51, maths: 50, science: 40, social: 58, total: 343, percentage: 49.00},
      "9145": { name: "મહાવીર નીતિનભાઈ ચૌહાણ", gujarati: 50, english: 65, hindi: 50, sanskrit: 61, maths: 62, science: 47, social: 81, total: 416, percentage: 59.43},
      "9146": { name: "મયંક સંજયભાઈ રાઠોડ", gujarati: 53, english: 69, hindi: 53, sanskrit: 67, maths: 61, science: 51, social: 72, total: 426, percentage: 60.86},
      "9147": { name: "મયુર ભરતભાઈ ધાંધલ્યા", gujarati: 57, english: 75, hindi: 56, sanskrit: 83, maths: 67, science: 67, social: 94, total: 499, percentage: 71.29},
      "9148": { name: "મીત ધર્મેન્દ્રભાઈ સાખટ", gujarati: 71, english: 92, hindi: 79, sanskrit: 84, maths: 96, science: 81, social: 98, total: 601, percentage: 85.86},
      "9149": { name: "નૈતિક જયેશભાઈ ઝાલા", gujarati: 54, english: 53, hindi: 47, sanskrit: 56, maths: 44, science: 39, social: 58, total: 351, percentage: 50.14},
      "9150": { name: "નૈતિક મિલનભાઈ પંડ્યા", gujarati: 63, english: 57, hindi: 53, sanskrit: 67, maths: 63, science: 72, social: 83, total: 458, percentage: 65.43},
      "9151": { name: "નીરવ રાજેશભાઈ મકવાણા", gujarati: 59, english: 63, hindi: 62, sanskrit: 69, maths: 32, science: 41, social: 69, total: 395, percentage: 56.43},
      "9152": { name: "નીતિન કિશોરભાઈ જાદવ", gujarati: 42, english: 35, hindi: 47, sanskrit: 41, maths: 39, science: 46, social: 60, total: 310, percentage: 44.29},
      "9153": { name: "પ્રાકૃત રાજેશભાઈ સોરઠિયા", gujarati: 61, english: 82, hindi: 66, sanskrit: 77, maths: 76, science: 73, social: 95, total: 530, percentage: 75.71},
      "9154": { name: "પ્રતિક સુરેશભાઈ બેરાણી", gujarati: 53, english: 55, hindi: 46, sanskrit: 63, maths: 34, science: 36, social: 61, total: 348, percentage: 49.71},
      "9155": { name: "રેહાન સરફરાઝભાઈ ચુડેસરા", gujarati: 47, english: 56, hindi: 48, sanskrit: 59, maths: 56, science: 46, social: 59, total: 371, percentage: 53.00},
      "9156": { name: "રુદ્ર અજયભાઈ પંડ્યા", gujarati: 60, english: 68, hindi: 59, sanskrit: 59, maths: 53, science: 69, social: 82, total: 450, percentage: 64.29},
      "9157": { name: "રૂદ્રેશ ભૂપેન્દ્રભાઈ બાંભણીયા", gujarati: 28, english: 37, hindi: 38, sanskrit: 51, maths: 72, science: 35, social: 48, total: 309, percentage: 44.14},
      "9158": { name: "રૂષિ ઓમભાઈ ત્રિવેદી", gujarati: 31, english: 43, hindi: 35, sanskrit: 43, maths: 32, science: 28, social: 66, total: 278, percentage: 39.71},
      "9159": { name: "શાહનવાઝ આરીફભાઈ બિલખિયા", gujarati: 62, english: 73, hindi: 58, sanskrit: 74, maths: 65, science: 56, social: 81, total: 469, percentage: 67.00},
      "9160": { name: "શૌર્ય જીજ્ઞેશભાઈ ત્રિવેદી", gujarati: 68, english: 83, hindi: 73, sanskrit: 85, maths: 94, science: 78, social: 93, total: 574, percentage: 82.00},
      "9161": { name: "ઉમંગ હરેશભાઈ ચૌહાણ", gujarati: 56, english: 60, hindi: 57, sanskrit: 62, maths: 66, science: 50, social: 78, total: 429, percentage: 61.29},
      "9162": { name: "વિરભદ્રસિંહ જશપાલસિંહ ચૌહાણ", gujarati: 60, english: 65, hindi: 59, sanskrit: 63, maths: 47, science: 50, social: 81, total: 425, percentage: 60.71},
    };

    function searchResult() {
      const seatNumber = document.getElementById('seatInput').value;
      const student = students[seatNumber];

      if (student) {
        let resultHTML = `<h3>Results for ${student.name}</h3>`;
        resultHTML += `<table>
                          <tr><th>Subject</th><th>Marks</th></tr>
                          <tr><td>Gujarati</td><td>${student.gujarati}</td></tr>
                          <tr><td>English</td><td>${student.english}</td></tr>
                          <tr><td>Hindi</td><td>${student.hindi}</td></tr>
                          <tr><td>Sanskrit</td><td>${student.sanskrit}</td></tr>
                          <tr><td>Maths</td><td>${student.maths}</td></tr>
                          <tr><td>Science</td><td>${student.science}</td></tr>
                          <tr><td>Social Studies</td><td>${student.social}</td></tr>
                          <tr><td>Total</td><td>${student.total}</td></tr>
                          <tr><td>Percentage</td><td>${student.percentage}%</td></tr>
                        </table>`;
        document.getElementById('result').innerHTML = resultHTML;
      } else {
        document.getElementById('result').innerHTML = `<p class="no-result">No result found for this seat number.</p>`;
      }
    }
  </script>

</body>
</html>
