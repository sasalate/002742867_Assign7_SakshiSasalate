# 002742867_Assign7_SakshiSasalate

ABOUT WEBSITE

The created website is a blog website which has the following two pages:-
i.login.html page-For users to login.On successful login the user is redirected to the next page
ii.index.html page- This page displays articles of all the blogs a user can see according to one's own interest.
                    It has the following features:-
                    In the head section there is an option where users can select the theme(dark/light) according to their preference.
                    It has the logout option to go back to the login.html page.
                    The next section belowis for users to read articles which is created by using the grid feature of css.It is divided into the ratio of 1:3.Where the                     article content is on the right side and image on the left.
                    
                    Last section is of footer which has information about total visits and total users
                    And a feedback form along with social media contacts.
                    
 
 SCSS/SASS FEATURES USED:-
 
 CSS GRID & FLEXBOX- Implemented the articles section by using the grid for the navigation bar (syntax- grid-template-columns: 2fr 3fr;),dividing the card. The flexbox is used for article's section (display:flex).
 
  VARIABLES AND CUSTOM PROPERTIES- Set the colour of background and text by setting variables name. 
 (syntax-$background: #fff; $text: #1c1a1f;)
 
NESTING implemented nesting in index.scss in the following tags- .loginform, .loginbtn, .nav, .box,.social,.articleSection, .footer.
 Interpolation- Implemented interpolation for setting the font wherever required 
 (Syntax-$font-name: "Poppins", sans-serif; )
 
MIXINS- Implemented a maxin called flex-center and ussed to for displaying propertries by using @include keyword.
 (@mixin flex-center {
  display: flex;
  justify-content: center;
  align-items: center;
  }
used as  @include flex-center;
)

PLACEHOLDER SELECTORS- Created a display-placeholder and used it by using the extend keyword.
(%display_placeholder{
  display: grid;
  place-items: center;
}
usage- @extend %display_placeholder;
)

SCSS files for different purpose like theme, mobile,index ,login placed separtely to make it look more organized.             
              
                
