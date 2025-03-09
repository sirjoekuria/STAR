# STAR
MY .CSS
body {
    font-family: 'Times New Roman', Times, serif;
    line-height: 1.6;
    max-width: 800px;
    margin: 0 auto;
    padding: 20px;
    background-color: #f4f4f4;
}
/*heading selectors*/
h1 {
    color: #333;
    text-align: center;
    border-bottom: 2px solid #007bff;
    padding-bottom: 10px;
}
h2 {
    color: #007bff;
}
/* class selector */
#skill-list {
    background-color: #e9ecef;
    padding:15px ;
    border-radius: 5xp;
}
/* ID selectors */
#projects {
    background-color: #ffffff;
    border: 1px solid #ddd;
    padding: 20px;
    border-radius: 8px;
}
/* text styling */
p {
    color: #666;
    font-size: 16px;
}
/* link styling */
a {
    color: #007bff;
    text-decoration:none ;
    transition: colour 0.3s ease;
}
a:hover {
    color: #0056b3;
    text-decoration: underline;
}
.skill-list {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
}
.skill-list li {
    background-color: #007bff;
    color: white;
    margin: 5px;
    padding: 8px 15px;
    border-radius: 20px;
}
#projects li {
    transition: transform 0.2s;
    padding: 10px;
    border-left: 4px solid #007bff;
}
#projects li:hover {
    transform: translateX(10px);
    background-color: #f1f3f5;
}
