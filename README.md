# s2-s6
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AQ test</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            padding: 0;
            background-color: #ffffff;
            color: #333;
        }
        h1 {
            text-align: center;
            color: #ee7623;
        }
        .question {
            margin-bottom: 20px;
        }
        .answers {
            margin-left: 20px;
        }
        .answers label {
            display: block;
        }
        #result {
            margin-top: 20px;
            padding: 15px;
            border: 1px solid #984a12;
            border-radius: 5px;
            background-color: white;
            color: #070707;
        
        }
        button {
            display: block;
            margin: 20px auto;
            padding: 10px 20px;
            background-color: #ee7623;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #91440d;
        }
    </style>
</head>
<body>
    <h1>AQ test</h1>
    <form id="aq-test">
        
        <div class="question">
            <p><b>1. Та санхүүгийн хямралд орсон. Та энэ байдалд хэр зэрэг нөлөөлж чадах вэ?</b>
                <br>1 - Огт үгүй<br> 5 - Маш их</p>
            <div class="answers">
                <label><input type="radio" name="q1" value="5">5</label>
                <label><input type="radio" name="q1" value="4">4</label>
                <label><input type="radio" name="q1" value="3">3</label>
                <label><input type="radio" name="q1" value="2">2</label>
                <label><input type="radio" name="q1" value="1">1</label>
            </div>
        </div>
       
        <div class="question">
            <p><b>2. Таныг албан тушаал ахихад хэн нэгэн үл тоосон хандлага гаргав. Нөхцөл байдлыг сайжруулахын тулд та хэр хариуцлагатай хандах вэ?</b>
                <br>1 - Огт хариуцлагатай хандахгүй<br> 5 - Маш их хариуцлагатай</p>
            <div class="answers">
                <label><input type="radio" name="q2" value="5">5</label>
                <label><input type="radio" name="q2" value="4">4</label>
                <label><input type="radio" name="q2" value="3">3</label>
                <label><input type="radio" name="q2" value="2">2</label>
                <label><input type="radio" name="q2" value="1">1</label>
              </div>
        </div>

        <div class="question">
            <p><b>3. Таны саяхан дуусгасан  төслийг шүүмжилж байна. Энэ нөхцөл байдлын үр дагавар нь: </b>
                <br>1 - Миний амьдралын бүх тал дээр нөлөөлнө<br> 5 - Огт нөлөөлөхгүй</p>
            <div class="answers">
                <label><input type="radio" name="q3" value="5">5</label>
                <label><input type="radio" name="q3" value="4">4</label>
                <label><input type="radio" name="q3" value="3">3</label>
                <label><input type="radio" name="q3" value="2">2</label>
                <label><input type="radio" name="q3" value="1">1</label>
              </div>
        </div>

        <div class="question">
            <p><b>4. Та санамсаргүйгээр чухал имэйлийг устгасан. Энэ нөхцөл байдлын үр дагавар нь:</b>
                <br>1 - Үүрд үргэлжилнэ<br> 5 - Маш богино хугацаанд үргэлжилнэ</p>
            <div class="answers">
                <label><input type="radio" name="q4" value="5">5</label>
                <label><input type="radio" name="q4" value="4">4</label>
                <label><input type="radio" name="q4" value="3">3</label>
                <label><input type="radio" name="q4" value="2">2</label>
                <label><input type="radio" name="q4" value="1">1</label>
              </div>
        </div>

        <div class="question">
            <p><b>5. Таны ажиллаж байсан маш чухал төсөл цуцлагдсан.Энэ нөхцөл байдлын үр дагавар нь:</b>
                <br>1 - Миний амьдралын бүх тал дээр нөлөөлнө<br> 5 - Огт нөлөөлөхгүй</p>
            <div class="answers">
                <label><input type="radio" name="q5" value="5">5</label>
                <label><input type="radio" name="q5" value="4">4</label>
                <label><input type="radio" name="q5" value="3">3</label>
                <label><input type="radio" name="q5" value="2">2</label>
                <label><input type="radio" name="q5" value="1">1</label>
              </div>
        </div>

        <div class="question">
            <p><b>6. Та өөрийн хүндэлдэг хүнтэйгээ  чухал асуудлын талаар  ярилцах гэтэл үл тоов. Энэ байдлыг сайжруулахын тулд та хэр хариуцлагатай хандах вэ?</b>
                <br>1 - Огт  хариуцлагатай хандахгүй<br> 5 - Маш их хариуцлагатай</p>
            <div class="answers">
                <label><input type="radio" name="q6" value="5">5</label>
                <label><input type="radio" name="q6" value="4">4</label>
                <label><input type="radio" name="q6" value="3">3</label>
                <label><input type="radio" name="q6" value="2">2</label>
                <label><input type="radio" name="q6" value="1">1</label>
              </div>
        </div>

        <div class="question">
            <p><b>7. Хүмүүс таны үзэл бодолд дурамжхан ханддаг.Энэ байдалд та хэр зэрэг нөлөөлж чадах вэ?</b>
                <br>1 - Огт нөлөөлж чадахгүй<br> 5 - Маш их</p>
            <div class="answers">
                <label><input type="radio" name="q7" value="5">5</label>
                <label><input type="radio" name="q7" value="4">4</label>
                <label><input type="radio" name="q7" value="3">3</label>
                <label><input type="radio" name="q7" value="2">2</label>
                <label><input type="radio" name="q7" value="1">1</label>
              </div>
        </div>

        <div class="question">
            <p><b>8. Танд амралт маш их хэрэгтэй байхад амралтаа авч чадахгүй байв.Энэ нөхцөл байдлын үр дагавар нь:</b>
                <br>1 - Урт хугацаанд үргэлжилнэ<br> 5 - Маш богино хугацаанд үргэлжилнэ</p>
            <div class="answers">
                <label><input type="radio" name="q8" value="5">5</label>
                <label><input type="radio" name="q8" value="4">4</label>
                <label><input type="radio" name="q8" value="3">3</label>
                <label><input type="radio" name="q8" value="2">2</label>
                <label><input type="radio" name="q8" value="1">1</label>
              </div>
        </div>

        <div class="question">
            <p><b>9.  Та чухал уулзалт руугаа явж байв. Гэтэл улаан гэрлэн дохио бүр дээр зогсож таараад байв.Энэ нөхцөл байдлын үр дагавар нь:</b>
                <br>1 - Миний амьдралын бүх тал дээр нөлөөлнө<br> 5 - Огт нөлөөлөхгүй</p>
            <div class="answers">
                <label><input type="radio" name="q9" value="5">5</label>
                <label><input type="radio" name="q9" value="4">4</label>
                <label><input type="radio" name="q9" value="3">3</label>
                <label><input type="radio" name="q9" value="2">2</label>
                <label><input type="radio" name="q9" value="1">1</label>
              </div>
        </div>

        <div class="question">
            <p><b>10. Та маш их судалгаа хийсэн ч өөрт хэрэгтэй чухал баримт бичгийг олж чадсангүй.Энэ нөхцөл байдлын үр дагавар нь:</b>
                <br>1 - Үүрд үргэлжилнэ<br> 5 - Маш богино хугацаанд үргэлжилнэ</p>
            <div class="answers">
                <label><input type="radio" name="q10" value="5">5</label>
                <label><input type="radio" name="q10" value="4">4</label>
                <label><input type="radio" name="q10" value="3">3</label>
                <label><input type="radio" name="q10" value="2">2</label>
                <label><input type="radio" name="q10" value="1">1</label>
              </div>
        </div>

        <div class="question">
            <p><b>11. Танай ажлын байранд боловсон хүчин дутмаг байв.Энэ байдлыг сайжруулахын тулд та хэр хариуцлагатай хандах вэ?</b>
                <br>1 - Огт  хариуцлагатай хандахгүй<br> 5 - Маш их хариуцлагатай</p>
            <div class="answers">
                <label><input type="radio" name="q11" value="5">5</label>
                <label><input type="radio" name="q11" value="4">4</label>
                <label><input type="radio" name="q11" value="3">3</label>
                <label><input type="radio" name="q11" value="2">2</label>
                <label><input type="radio" name="q11" value="1">1</label>
            </div>
        </div>

        <div class="question">
            <p><b>12.  Та чухал уулзалтаасаа  хоцорч байна.Энэ нөхцөл байдлын үр дагавар нь:</b>
                <br>1 - Миний амьдралын бүх тал дээр нөлөөлнө<br> 5 - Огт нөлөөлөхгүй</p>
                <div class="answers">
                    <label><input type="radio" name="q12" value="5">5</label>
                    <label><input type="radio" name="q12" value="4">4</label>
                    <label><input type="radio" name="q12" value="3">3</label>
                    <label><input type="radio" name="q12" value="2">2</label>
                    <label><input type="radio" name="q12" value="1">1</label>
                </div>
        </div>

        <div class="question">
            <p><b>13. Таны хувийн болон ажлын үүрэг тэнцвэргүй байна. Энэ байдалд та хэр зэрэг нөлөөлж чадах вэ?</b>
                <br>1 - Огт үгүй<br> 5 - Маш их</p>
                <div class="answers">
                    <label><input type="radio" name="q13" value="5">5</label>
                    <label><input type="radio" name="q13" value="4">4</label>
                    <label><input type="radio" name="q13" value="3">3</label>
                    <label><input type="radio" name="q13" value="2">2</label>
                    <label><input type="radio" name="q13" value="1">1</label>
                </div>
        </div>

        <div class="question">
            <p><b>14. Та өөрийгөө санхүүгийн тал дээр маш их асуудалтай гэж боддог. Энэ нөхцөл байдлын үр дагавар нь:</b>
                <br>1 - Үүрд үргэлжилнэ<br> 5 - Маш богино хугацаанд үргэлжилнэ</p>
                <div class="answers">
                    <label><input type="radio" name="q14" value="5">5</label>
                    <label><input type="radio" name="q14" value="4">4</label>
                    <label><input type="radio" name="q14" value="3">3</label>
                    <label><input type="radio" name="q14" value="2">2</label>
                    <label><input type="radio" name="q14" value="1">1</label>
                </div>
        </div>

        <div class="question">
            <p><b>15. Та дасгал хийх ёстойгоо мэддэг ч тогтмол дасгал хийдэггүй.Энэ байдалд та хэр зэрэг нөлөөлж чадах вэ?</b>
                <br>1 - Огт үгүй<br> 5 - Маш их</p>
                <div class="answers">
                    <label><input type="radio" name="q15" value="5">5</label>
                    <label><input type="radio" name="q15" value="4">4</label>
                    <label><input type="radio" name="q15" value="3">3</label>
                    <label><input type="radio" name="q15" value="2">2</label>
                    <label><input type="radio" name="q15" value="1">1</label>
                </div>
        </div>

        <div class="question">
            <p><b>16. Танай байгууллага зорилгодоо хүрч ажиллахгүй байв. Энэ байдлыг сайжруулахын тулд та хэр хариуцлагатай хандах вэ?</b>
                <br>1 - Огт  хариуцлагатай хандахгүй<br> 5 - Маш их хариуцлагатай </p>
                <div class="answers">
                    <label><input type="radio" name="q16" value="5">5</label>
                    <label><input type="radio" name="q16" value="4">4</label>
                    <label><input type="radio" name="q16" value="3">3</label>
                    <label><input type="radio" name="q16" value="2">2</label>
                    <label><input type="radio" name="q16" value="1">1</label>
                </div>
        </div>

        <div class="question">
            <p><b>17. Таны компьютер энэ долоо хоногт гурав дахь удаагаа эвдэрсэн.Энэ байдалд та хэр зэрэг нөлөөлж чадах вэ?</b>
                <br>1 - Огт үгүй<br> 5 - Маш их</p>
                <div class="answers">
                    <label><input type="radio" name="q17" value="5">5</label>
                    <label><input type="radio" name="q17" value="4">4</label>
                    <label><input type="radio" name="q17" value="3">3</label>
                    <label><input type="radio" name="q17" value="2">2</label>
                    <label><input type="radio" name="q17" value="1">1</label>
                </div>
        </div>

        <div class="question">
            <p><b>18. Таны төлөвлөсөн  уулзалт цагийг дэмий үрсэн уулзалт боллоо.Энэ байдлыг сайжруулахын тулд та хэр хариуцлагатай хандах вэ?</b>
                <br>1 - Огт  хариуцлагатай хандахгүй<br> 5 - Маш их хариуцлагатай </p>
                <div class="answers">
                    <label><input type="radio" name="q18" value="5">5</label>
                    <label><input type="radio" name="q18" value="4">4</label>
                    <label><input type="radio" name="q18" value="3">3</label>
                    <label><input type="radio" name="q18" value="2">2</label>
                    <label><input type="radio" name="q18" value="1">1</label>
                </div>
        </div>

        <div class="question">
            <p><b>19. Та өөрийнхөө хувьд чухал зүйлээ алдсан.Энэ нөхцөл байдлын үр дагавар нь:</b>
                <br>1 - Үүрд үргэлжилнэ<br> 5 - Маш богино хугацаанд үргэлжилнэ</p>
                <div class="answers">
                    <label><input type="radio" name="q19" value="5">5</label>
                    <label><input type="radio" name="q19" value="4">4</label>
                    <label><input type="radio" name="q19" value="3">3</label>
                    <label><input type="radio" name="q19" value="2">2</label>
                    <label><input type="radio" name="q19" value="1">1</label>
                </div>
        </div>

        <div class="question">
            <p><b>20.  Таны дарга таны гаргасан шийдвэртэй огт санал нийлэхгүй байв. Энэ нөхцөл байдлын үр дагавар нь:</b>
                <br>1 - Миний амьдралын бүх тал дээр нөлөөлнө<br> 5 - Огт нөлөөлөхгүй</p>
                <div class="answers">
                    <label><input type="radio" name="q20" value="5">5</label>
                    <label><input type="radio" name="q20" value="4">4</label>
                    <label><input type="radio" name="q20" value="3">3</label>
                    <label><input type="radio" name="q20" value="2">2</label>
                    <label><input type="radio" name="q20" value="1">1</label>
                </div>
        </div>

        <button type="button" onclick="calculateScore()">Илгээх</button>
    </form>
   <div id="result"></div>

   
<script>
    function calculateScore() {
        let scores = {};
        let allAnswered = true;
        for (let i = 1; i <= 20; i++) {
            const selectedRadio = document.querySelector(`input[name="q${i}"]:checked`);
            if (selectedRadio) {
                scores[i] = parseInt(selectedRadio.value);
            }
            else {
            allAnswered = false;  
        }
    }
        
    if (!allAnswered) {
     
        alert("Бүх асуултанд хариулна уу");
        return;
    }
    
    function sumValues(questions) {
        return questions.reduce((sum, q) => sum + (scores[q] || 0), 0);
    }
        const C = sumValues([1, 7, 13, 15, 17]);
        const O = sumValues([2, 6, 11, 16, 18]);
        const R = sumValues([3, 5, 9, 12, 20]);
        const E = sumValues([4, 8, 10, 14, 19]);
    
        const ARP = (C + O + R + E) * 2;
    
        const resultDiv = document.getElementById('result');
        resultDiv.innerHTML = `
            <h3>Results:</h3>
            <p><strong>C:</strong> ${C}</p>
            <p><strong>O:</strong> ${O}</p>
            <p><strong>R:</strong> ${R}</p>
            <p><strong>E:</strong> ${E}</p>
            <p><strong>ARP:</strong> ${ARP}</p>
        `;
    }
    </script>
    </body>
    </html>
