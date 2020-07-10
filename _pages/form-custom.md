---
layout: default
title: Cyber Arts Camp
---

<article id="Form">
        <div class="group text">      
                <input type="text" required>
                <label>First name</label>
        </div>
        <div class="group text">      
                <input type="text" required>
                <label>Last name</label>
        </div>
        <div class="group text">      
                <input type="text" required>
                <label>Email</label>
        </div>
        <div class="group radio">   
                <label>Are you a...</label>  
                <div> 
                        <input type="radio" id="student" name="martiantype" value="student">
                        <label for="student">Student</label>
                        <input type="radio" id="parent" name="martiantype" value="parent">
                        <label for="parent">Parent</label>
                        <input type="radio" id="teacher" name="martiantype" value="teacher">
                        <label for="teacher">Teacher</label>
                </div>
        </div>
        <div class="group textarea">
                <label>What brings you to Mars?</label>
                <textarea rows = "5" cols = "50" name = "description"></textarea>
        </div>
        <a class="send-btn btn-large">Send</a>
</article>

<footer>
</footer>
