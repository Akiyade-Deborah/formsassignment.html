
<!-- DOCTYPE html -->
<html>
    <head>
        <title>form assignment</title>
    </head>
        <body>
          <forms>
            <img src="https://www.arch2o.com/wp-content/uploads/2023/01/Arch2O-whats-the-tallest-skyscraper-in-the-world-heres-a-list-of-the-worlds-30-highest-buildings-700x467.jpg" alt="job application form">
         <h1>Job Applicaton Form</h1>
     <hr>
     <p>* indicates required question</P>
        <section> 
            <label for="fullname"><strong>Full Name *</strong></label>
            <br><br>
            <input type="text" name="fullname" placeholder="First Name" required>
            <br><br>
            <input type="text" name="fullname" placeholder="Last Name" required>
        </section>
            <br>
        <section>
            <label for="email"><strong>E-mail *</strong></label>
            <br><br>
            <input type="email" name="e-mail" placeholder="✉" required>
        </section>
            <br>
        <section>
            <label for="contact-number"><strong>Contact Number *</strong></label>
            <br><br>
            <input type="tel" name="contact-number" placeholder="✆" required>
        </section>
            <br>
        <section>
            <label for="address"><strong>Address</strong></label>
            <br><br>
            <input type="text" name="address" placeholder=" 📍  Street Address">
            <br><br>
            <input type="text" name="address" placeholder="City"><input type="text" name="address" placeholder="State">
            <br><br>
            <input type="number" name="address" placeholder="Postal Code">
            <br><br>
            <select id="address" name="address">
            <option value="">Select a Country</option>
            <option value="nig">Nigeria</option>
            <option value="tur">Turkey</option>
            <option value="sa">South Africa</option>
            <option value="ghn">Ghana</option>
            </select>
        </section>
            <br>
        <section>
            <label for="what-position-are-you-applying-for?"><strong>What position are you applying for?</strong>
            <br><br>
            <input type="radio" name="what-position-are-you-applying-for?" value="customer-service-representative">Customer Service Representative</label>
            <br>
            <label><input type="radio" name="what-position-are-you-applying-for?" value="data-analyst">Data Analyst</label>
            <br>
            <label><input type="radio" name="what-position-are-you-applying-for?" value="sales-representative">Sales Representative</label>
        </section>
            <br>
        <section>
            <label for="available-start-date"><strong>Available start date *</strong></label>
            <br><br>
            <input type="date" name="available-start-date" required>
        </section>
            <br>
        <section>
            <label for="what-is-your-current-employment-status?" required><strong>What is your current employment status? *</strong></label>
            <br><br>
            <label><input type="checkbox" name="what-is-your-current-employment-status?" value="employed">Employed</label>
            <br>
            <label><input type="checkbox"  name="what-is-your-current-employment-status?" value="unemployed">Unemployed</label>
            <br>
            <label><input type="checkbox" name="what-is-your-current-employment-status?" value="self-employed">Self-Employed</label>
            <br>
            <label><input type="checkbox" name="what-is-your-current-employment-status?" value="student">Student</label>
            <br>
            <label><input type="checkbox" name="what-is-your-current-employment-status?" value="other">Other</label>
        </section>
            <br>
        <section>
           <label for="Upload-your-resume" enctype="multipart/form-data"><strong>Upload your resume</strong></label>
           <br>
           <p><i>Only PDF,  DOC, DOCX, XLS, XLSX, PPT, PPTX.</i></p>
           <label><input type="file" name="upload-your-resume" placeholder="Drop Files Here"></label>
        </section>
           <br>
        <section>
           <label for="comment"><strong>Notes, Questions and Suggestions</strong></label>
           <br><br>
           <textarea id="comment" name="comment"></textarea>
        </section>
            <br>
        <section>
            <label for="button"></label>
            <input type="submit" name="submit" value="submit">
        </section>
 </forms>    
</body>
</html>
