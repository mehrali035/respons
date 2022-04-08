# respons
 @media(max-width:768px) {
    .hero-para {
        margin-right: 3rem;
    }
    .container h2,P {
        padding-left: 2rem;
    }

    .common-heading::before {
        position: absolute;
        content: " ";
        top: 105%;
        left: 2rem;
        width: 1.3rem;
        height: 1.5rem;
        background: var(--helper);
        border-radius: 50%;
    }

    .common-heading::after {
        position: absolute;
        content: " ";
        top: 118%;
        left: 2rem;
        min-width: 20rem;
        height: 0.3rem;
        background: var(--helper);
    }

    .adress h3 {
        padding-left: 2rem;
    }

    .portfolio-images {
        display: grid;
        grid-template-columns: 1fr 1fr;
        gap: 1rem;
        padding-left: 1rem;
    }

    .portfolio-images {
        width: 95%;
    }

    .social img {
        margin: 0 1rem;
    }

    .hero-heading {
        font-size: 3.4rem;
    }

}






@media(max-width:550px) {
    .header .hamburger {
        display: block;
    }

    .header ul {
        display: none;
    }

    .navbar ul {
        text-align: center;
        background-color: #d9dcf7;
        margin-top: 16rem;
        line-height: 2rem;
        width: 18rem;
        height: 11rem;
    }

    nav ul.show {
        display: block;
    }

    .common-heading {
        font-size: 2.8rem;
        font-weight: 400;
    }

    .hero-heading {
        font-size: 2.4rem;
    }

    .hero-top-data {
        font-size: 1rem;
    }


}

@media(max-width:350px) {
    .common-heading {
        font-size: 1.8rem;
        font-weight: 200;
    }

    .hero-heading {
        font-size: 1.4rem;
    }

    .hero-top-data {
        font-size: 0.8rem;
    }
    .grid-two-column{
        grid-template-columns: 1fr;
    }
    .hero-top-data{
        font-size: 1rem;
        margin-right: 15rem;
    }
    .hero-heading{
        margin-right: 12rem;
    }
    .bio-data-stats{
        padding-left: 2rem;
    }
    .bio-data-btn{
        padding-left:6rem;
    }
    .portfolio-images{
        display: grid;
        grid-template-columns: 1fr;
        padding-left: 3rem;
    }
    .portfolio-images img{
        width: 90%;
    }
    .image-overlay .overlay{
        width: 90%;
    }
    .common-heading::before {
        position: absolute;
        content: " ";
        top: 100%;
        left: 0.8rem;
        width: 1rem;
        height: 1.5rem;
        background: var(--helper);
        border-radius: 50%;
    }

    .common-heading::after {
        position: absolute;
        content: " ";
        top: 118%;
        left: 1rem;
        min-width: 15rem;
        height: 0.3rem;
        background: var(--helper);
    }
    .form input{
        width: 25rem;
    }
    .social h4{
        padding-left: 1rem;
    }
    

    


}
