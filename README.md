# newloans4<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Loans & Insurance</title>
<style>
  body {
    background: #f8fafc;
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    color: #205081;
  }
  .main-title {
    text-align: center;
    font-size: 1.5em;
    font-weight: bold;
    margin: 30px 0 10px 0;
    color: #275db2;
  }
  .display-bar {
    margin: 0 auto 24px auto;
    width: 85%;
    text-align: center;
    border: 2px solid #51baf6;
    border-radius: 7px;
    background: #f6fdfe;
    padding: 17px 0;
    color: #295176;
    font-size: 1.13em;
    font-weight: 500;
  }
  .dashboard-cards {
    display: flex;
    justify-content: center;
    gap: 48px;
    margin: 28px auto;
    flex-wrap: wrap;
    max-width: 900px;
  }
  .card {
    background: #fcfdff;
    border: 2px solid #6eb7e7;
    border-radius: 11px;
    width: 320px;
    padding: 28px 16px 20px 16px;
    box-shadow: 0 2px 14px #daeefd60;
    transition: box-shadow 0.27s;
    cursor: pointer;
    position: relative;
  }
  .card:hover {
    box-shadow: 0 8px 24px #74b4f99a;
  }
  .card-title {
    background: #2890cc;
    color: #fff;
    font-size: 1.15em;
    font-weight: bold;
    padding: 12px 0;
    border-radius: 7px;
    text-align: center;
    margin-bottom: 14px;
  }
  ul {
    margin: 4px 0 0 30px;
    padding: 0;
    color: #273965;
    font-size: 1.09em;
    text-align: left;
  }
  .back-btn {
    background: white;
    color: #0288d1;
    border: 2.5px solid #03a9f4;
    padding: 11px 0;
    font-weight: bold;
    border-radius: 11px;
    text-align: center;
    width: 210px;
    font-size: 1.1em;
    cursor: pointer;
    margin: 25px auto 20px auto;
    display: block;
    transition: background-color 0.3s,color 0.3s;
  }
  .back-btn:hover {
    background: #03a9f4;
    color: white;
  }
  .contact-form {
    max-width: 360px;
    margin: 30px auto 0 auto;
    padding: 16px 18px;
    background: #eef7ff;
    border-radius: 10px;
    border: 1.5px solid #85bbeb;
    font-size: 1.03em;
  }
  .contact-form label {
    font-weight: 600;
    color: #205081;
    display: block;
    margin-bottom: 8px;
    margin-top: 8px;
  }
  .contact-form input, .contact-form textarea {
    width: 100%;
    padding: 9px;
    margin-bottom: 14px;
    border: 2px solid #85bbeb;
    border-radius: 6px;
    font-size: 15px;
    box-sizing: border-box;
  }
  .contact-form input:focus, .contact-form textarea:focus {
    border-color: #3a8ddb;
    outline: none;
  }
  .contact-form button {
    background-color: #275db2;
    color: white;
    border: none;
    padding
