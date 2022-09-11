<template>
  <div class="bassick-contact-wrapper">
    <div class="bassick-contact-title"><span>Contact</span></div>
    <div class="bassick-contact-form">
      <div>
        <form>
          <div class="bassick-contact-form-1">
            <input type="text" name="name" placeholder="Your Name" />
            <!-- <input type="text" placeholder="Last Name" /> -->
            <input type="email" name="email" placeholder="Email" />
            <!-- </div> -->
            <!-- <div class="bassick-contact-form-2"> -->
            <textarea
              name=""
              id=""
              cols="30"
              rows="10"
              placeholder="Whats up?"
            ></textarea>
            <input type="submit" value="Submit" />
          </div>
        </form>
      </div>
      <div class="bassick-contact-card">
        <div class="bassick-contact-card-title">Bassick Records Ja.</div>
        <table>
          <tbody>
            <tr>
              <td><i class="fas fa-phone"></i></td>
              <td>:</td>
              <td>+1(876) 999-1234</td>
            </tr>
            <tr>
              <td><i class="fas fa-envelope"></i></td>
              <td>:</td>
              <td>info@bassickrecja.com</td>
            </tr>
            <tr>
              <td><i class="fas fa-map-marker"></i></td>
              <td>:</td>
              <td>
                10 Place St. <br />
                Kingston 30 <br />
                Jamaica, WI
              </td>
            </tr>
          </tbody>
        </table>

        <!-- <div> : </div> -->
        <!-- <div>:</div> -->
        <!-- <div>:</div> -->
      </div>
    </div>
  </div>
</template>

<style>
.bassick-contact-wrapper {
  padding: 50px;
  /* display: flex; */
  /* flex-direction: column; */
  /* align-items: center; */
  color: white;
  background-color: #000800;
}
.bassick-contact-wrapper > div > span {
  font-size: 36px;
  font-weight: 200;
}
.bassick-contact-title {
  display: flex;
  justify-content: center;
}
.bassick-contact-form {
  display: flex;
  /* flex-direction: row; */
  justify-content: space-evenly;
  flex-wrap: wrap;
}
.bassick-contact-form-1 {
  display: flex;
  flex-direction: column;
  /* justify-content: space-between; */
}
.bassick-contact-form-1 > input,
.bassick-contact-form-1 > textarea {
  /* border-radius: px; */
  margin: 8px 0;
  padding: 12px;
  border: none;
  /* width: 100%; */
}
.bassick-contact-form-1 input[type="submit"] {
  cursor: pointer;
}
.bassick-contact-form > div {
  margin: 20px 0;
  min-width: 400px;
  /* min-width: 100%; */
}
.bassick-contact-card {
  background-color: rgba(255, 255, 255, 0.1);
  color: white;
  padding: 30px;
  /* height: 100%; */
  width: 300px;
  /* line-height: px; */
}
.bassick-contact-card-title {
  font-size: 36px;
}
tr {
  height: 2.5rem;
}
td {
  vertical-align: top;
}
td:nth-of-type(3) {
  padding-left: 20px;
  /* color: red; */
}
</style>
