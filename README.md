# CSSGridFullWebsite
What I learned:

Using CSS Variables, Using :root{} to be able to use vars throughout stylesheet;

Ex: :root{--dark: #333;}
html{color: var(--dark);}

display:grid; -generates block level grid
grid-gap;-spacing between everything

getting nav to display evenly hoziontally: 
Ex: grid-template-columns: repeat(4, 1f);

Creating a layout for main picture and content with showcase:
Ex: 
    grid-template-areas:
    'showcase showcase top-box-a'
    'showcase showcase top-box-b';
}

Using flexbox with Css Grid to help align content inside a box
    display: flex;
    flex-direction: column;
    align-items: start;
    justify-content: center;

Making grid template columns more responive:
Ex: grid-template-columns:repeat(auto-fit, minmax(200px, 1fr));
