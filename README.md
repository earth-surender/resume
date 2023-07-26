<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Kanit:wght@300&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="script.js">

</head>
<body>
    <div class="navbar">

        <div class="logo">
            <a href="port.html" class="res"><h1>Resume</h1></a>
        </div>

    </div>

    

    <div class="data">
        <div class="part1">
            
            <img src="profilepic.jpg" class="img-prof">

            <div class="des-prof">
                <h2 class="descript">Pheerachat Jamfa</h2>
                <h3 class="descript" style="margin-top: 5px;">Hi, I'm Earth</h3>
                <p class="descript1">This is my dedicated resume website to showcase my certificate. Thank you for visiting my website.</ย>
                <h3 class="descript" style="font-size: 1.2rem;">Nakhon Sawan Rajabhat University<br>Information Technology</h3>

            <div class="contact">
                <a href="#"><img src="facebook.png" class="facebook"></a>
                <a href="#"><img src="google.png" class="gmail"></a>
                <a href="#"><img src="instagram.png" class="ig"></a>
            </div>
        </div>
        </div>
            
    </div>

    <div class="data-2">

        <div class="certificate">
            <h3>My certificate</h3>

            <div class="m-cer">
                <div onclick="showpopup1()" class="my-cer">
                    <img src="cer1.png" class="cer">
                    <p class="cer-des1">การเพิ่มประสิทธิภาพการทำงานด้วยปัญญาประดิษฐ์</p>
                </div>

                <div onclick="showpopup2()" class="my-cer">
                    <img src="cer2.png" class="cer">
                    <p class="cer-des1">การสร้างหน้าเว็บเบื้องต้นด้วย HTML และ CSS</p>
                </div>

                <div onclick="showpopup3()" class="my-cer">
                    <img src="cer3.png" class="cer">
                    <p class="cer-des1">คอมพิวเตอร์กราฟฟิก</p>
                </div>
                
            </div>



        </div>

        <div class="skill">
            <h3 class="des-skill">My skill</h3>

            <div class="skill-box">
                <span class="title">HTML</span>
                <div class="skill-bar">
                    <span class="skill-per html">
                        <span class="tooltip">80%</span>
                    </span>
                </div>
            </div>
            <div class="skill-box">
                <span class="title">CSS</span>
                <div class="skill-bar">
                    <span class="skill-per css">
                        <span class="tooltip">75%</span>
                    </span>
                </div>
            </div>
            <div class="skill-box">
                <span class="title">Adobe Photoshop</span>
                <div class="skill-bar">
                    <span class="skill-per photoshop">
                        <span class="tooltip">80%</span>
                    </span>
                </div>
            </div>
            <div class="skill-box">
                <span class="title">Adobe Illustrator</span>
                <div class="skill-bar">
                    <span class="skill-per illustrator">
                        <span class="tooltip">70%</span>
                    </span>
                </div>
            </div>
            <div class="skill-box">
                <span class="title">Adobe premiere pro</span>
                <div class="skill-bar">
                    <span class="skill-per premiere">
                        <span class="tooltip">50%</span>
                    </span>
                </div>
            </div>
            <div class="skill-box">
                <span class="title">Microsoft office</span>
                <div class="skill-bar">
                    <span class="skill-per Microsoft">
                        <span class="tooltip">85%</span>
                    </span>
                </div>

        </div>

    </div>

    <div id="popup" class="modal" style="display: none;">
        <div class="modal-bg"></div>

        <div class="modal-page">
            <div id="closepo" class="cc" onclick="closepopup()">
                <img src="cancel.png" class="cancel-bt">
            </div>
            <div class="modal-content">
                <img src="cer1.png" class="md-im">
                <p>ประกาศนียบัตรหลักสูตรการเพิ่มประสิทธิภาพการทำงานด้วยปัญญาประดิษฐ์</p>
            </div>
        </div>

    </div>

    <div id="popup2" class="modal" style="display: none">
        <div class="modal-bg"></div>

        <div class="modal-page">
            <div id="closepo3" class="cc" onclick="closepu()">
                <img src="cancel.png" class="cancel-bt">
            </div>
            <div class="modal-content">
                <img src="cer2.png" class="md-im">
                <p>ประกาศนียบัตรหลักสูตร สู่การเป็นนักพัฒนาเว็ย : การสร้างหน้าเว็บเบื้องต้นด้วย HTML และ CSS</p>
            </div>
        </div>

    </div>

    <div id="popup3" class="modal" style="display: none">
        <div class="modal-bg"></div>

        <div class="modal-page">
            <div id="closepo4" class="cc" onclick="closepp()">
                <img src="cancel.png" class="cancel-bt">
            </div>
            <div class="modal-content">
                <img src="cer3.png" class="md-im">
                <p>ประกาศนียบัตรหลักสูตรคอมพิวเตอร์กราฟฟิก</p>
            </div>
        </div>

    </div>


    <script>
            function showpopup1() {
            var popup = document.getElementById("popup");
            popup.style.display = "";
            }
            function closepopup() {
                var closepop = document.getElementById("closepo");
                popup.style.display = "none";
            }

            function showpopup2() {
            var popup = document.getElementById("popup2");
            popup.style.display = "";
            }
            function closepu() {
                var closep = document.getElementById("closepo3");
                popup2.style.display = "none";
            }

            function showpopup3() {
            var popup = document.getElementById("popup3");
            popup.style.display = "";
            }
            function closepp() {
                var closep = document.getElementById("closepo4");
                popup3.style.display = "none";
            }
    </script>

    

</body>
</html>
