```javascript
import {Container, Name, Age, Skills, AboutMe, Hobbies, Contacts} from './styles';

const Me = () => {
  const contactList = {
   phoneNumber: "(91)984601156",
   professionalEmail: "coutinho.codes@gmail.com",
   mainEmail: "emmanoelcesar967@gmail.com"
  };

  return(
  <Container>
    <Name> EmmanoelCoutinho </Name>
    <Age> 20 </Age>
    <Skills>
      <li> Javascript </li>
      <li> Typescript </li>
      <li> Html </li>
      <li> Css </li>
      <li> a little Node.js </li>
    </Skills>
    <AboutMe>
      I am a JavaScript developer who is trying to improve more and more, I really love web development!
    </AboutMe>
    <Hobbies>I love play acoustic guitar and play League of legends</Hobbies> //my current nick is Black Samurai, add me ^^
    <Contacts>
      <li> {contactList.phoneNumber} </li>
      <li> {contactList.professionalEmail} </li>
      <li> {contactList.mainEmail} </li>
    </Contacts>
  </Container>
  );
}

export default Me;
```
