# shiva
Digital Payment Wallet (Paytm Clone) with MERN Technology frontend 
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>
      Paytm: Secure &amp; Fast UPI Payments, Recharge Mobile &amp; Pay Bills
    </title>
    <script
      src="https://kit.fontawesome.com/24c494a6b6.js"
      crossorigin="anonymous"
    ></script>
    <style>
      .navbar {
        height: 70px;
        width: 100%;
        display: flex;
      }
      .left {
        width: 20%;
        height: 100%;
        display: flex;
        justify-content: center;
        text-align: center;
      }
      .logo {
        height: 25px;
        align-self: center;
      }
      .middle {
        width: 60%;
        height: 100%;
        display: flex;
        justify-content: space-evenly;
        align-items: center;
      }
      .right {
        width: 20%;
        height: 100%;
        display: flex;
        align-items: center;
        justify-content: center;
      }
      .sub-links {
        font-size: 20px;
        font-weight: bold;
      }
      .account {
        display: flex;
        justify-content: center;
        align-items: center;
        background-color: #00baf2;
        padding: 2px 2px 2px 20px;
        border-radius: 20px;
        color: white;
        font-weight: bold;
        font-size: 20px;
      }
      .avatar {
        margin-left: 10px;
      }
      .kyc {
        height: 50px;
        width: 100%;
        display: flex;
        align-items: center;
        justify-content: center;
        background-color: #f6f6f6;
      }
      .wallet {
        margin-right: 5px;
      }
      .section-2 {
        width: 100%;
        height: 700px;
        display: flex;
      }
      .left-section {
        width: 50%;
        height: 100%;
        display: flex;
        justify-content: center;
        align-items: center;
      }
      .right-section {
        width: 50%;
        height: 100%;
        display: flex;
        justify-content: flex-end;
        padding-top: 100px;
      }
      .paytm {
        height: 80px;
        width: 80px;
      }
      .head {
        font-size: 55px;
        font-weight: bold;
      }
      .para {
        font-size: 20px;
        font-weight: 500;
        width: 450px;
        line-height: 30px;
      }
      .btn {
        background-color: black;
        color: white;
        padding: 15px 24px 15px 24px;
        border-radius: 40px;
        border: 0px;
        display: flex;
        justify-content: center;
        align-items: center;
        margin-top: 30px;
      }
      svg {
        margin-left: 10px;
      }
      .right-logo {
        height: 528px;
        width: 528px;
      }
      .recharge-section {
        width: 100%;
        background-color: #00baf2;
        color: white;
      }
      .inner-section {
        width: 80%;
        margin: auto;
      }
      .heading {
        font-size: 36px;
        padding-top: 70px;
      }
      .rc-child {
        display: flex;
        justify-content: space-between;
        margin-top: 50px;
        padding-bottom: 50px;
      }
      .rc-logo {
        height: 64px;
        width: 64px;
      }
      .inner-div {
        line-height: 10px;
        font-weight: bold;
      }
      .book-section {
        width: 100%;
        background-color: #0f4a8a;
        color: white;
      }
      .bk-inner-div {
        font-weight: bolder;
        line-height: 5px;
      }
      .bk-logo {
        height: 64px;
        width: 64px;
      }
      .ins-section {
        width: 100%;
        background-color: #f5f7fa;
        color: white;
        padding-bottom: 100px;
      }
      .main-div {
        width: 75%;
        margin: auto;
        padding-top: 70px;
      }
      .ins-heading {
        font-size: 50px;
        color: black;
      }
      .section-1 {
        background-color: white;
        color: black;
        border-radius: 20px;
        display: flex;
        justify-content: center;
        align-items: center;
      }
      .left-ins {
        display: flex;
        justify-content: center;
        align-items: center;
        margin: auto;
        margin: 70px 34px 70px 34px;
      }
      .wallet-logo {
        width: 77px;
        height: 77px;
        margin-right: 10px;
      }
      .right-wall-img {
        width: 539px;
        height: 460px;
        margin: 70px 10px 70px 10px;
      }
      .text-midd {
        margin: auto;
        padding: 70px 10px 70px 10px;
        width: 400px;
      }
      .img-text {
        display: flex;
        align-items: center;
      }
      .section-2 {
        background-color: white;
        color: black;
        border-radius: 20px;
        display: flex;
        justify-content: center;
        align-items: center;
        margin-top: 50px;
      }
      .right-sec-2 {
        width: 539px;
        height: 460px;
        margin: 70px 10px 70px 10px;
      }
      .section-3 {
        background-color: white;
        color: black;
        border-radius: 20px;
        display: flex;
        justify-content: center;
        align-items: center;
        margin-top: 50px;
      }
      .right-sec-3 {
        width: 539px;
        height: 460px;
        margin: 70px 10px 70px 10px;
      }
      .postpaid-logo {
        width: 195px;
        height: 77px;
      }
      .btn-blue {
        background-color: #002970;
        color: white;
        padding: 15px 24px 15px 24px;
        border-radius: 40px;
        border: 0px;
        display: flex;
        justify-content: center;
        align-items: center;
        margin-top: 30px;
      }
      .sec-img-3 {
        width: 433px;
        height: 500px;
        margin: 70px 10px 70px 10px;
      }
    </style>
  </head>
  <body>
    <!-- navbar section -->
    <div class="navbar">
      <div class="left">
        <img
          class="logo"
          src="https://assetscdn1.paytm.com/frontendcommonweb/11272962.svg"
          alt="paytm-logo"
        />
      </div>
      <div class="middle">
        <p class="sub-links">Paytm for Consumer</p>
        <p class="sub-links">Paytm for Business</p>
        <p class="sub-links">Company</p>
        <p class="sub-links">Investor Relations</p>
        <p class="sub-links">Career</p>
      </div>
      <div class="right">
        <div class="account">
          Sign in
          <img
            class="avatar"
            src="https://assetscdn1.paytm.com/frontendcommonweb/9fd9626b.svg"
            alt="account"
          />
        </div>
      </div>
    </div>
    <!-- end navbar section -->

    <!-- kyc section -->
    <p class="kyc">
      <b class="wallet">No Wallet KYC Required</b> 😊 to pay using UPI on Paytm.
      Learn more.
    </p>
    <!-- end kyc section -->

    <!-- section - 2 -->
    <div class="section-2">
      <div class="left-section">
        <div>
          <img
            class="paytm"
            src="https://assetscdn1.paytm.com/images/catalog/view/310944/1626342046207.png"
            alt="images"
          />
          <h1 class="head">
            India's Most-loved<br />
            Payments App
          </h1>
          <p class="para">
            Recharge & pay bills, book flights & movie tickets, open a savings
            account, invest in stocks & mutual funds, and do a lot more.
          </p>
          <button class="btn">
            Download Paytm App
            <span
              ><svg
                width="14"
                height="16"
                viewBox="0 0 14 16"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M11.6593 15.3557C10.7589 16.1979 9.76546 16.0666 8.81854 15.6695C7.81182 15.2644 6.89149 15.2388 5.82828 15.6695C4.50426 16.2203 3.80155 16.0602 3.00415 15.3557C-1.49786 10.8883 -0.833353 4.08311 4.28331 3.82691C5.52427 3.89096 6.39311 4.48821 7.12406 4.53785C8.21052 4.32489 9.25047 3.71483 10.4133 3.79489C11.8105 3.90377 12.8554 4.43538 13.5531 5.3913C10.6791 7.05657 11.3603 10.7073 14 11.7321C13.4717 13.0691 12.7939 14.3902 11.6576 15.3669L11.6593 15.3557ZM7.02439 3.77888C6.88982 1.79336 8.55939 0.160122 10.4798 0C10.7439 2.28974 8.32017 4.00305 7.02439 3.77888Z"
                  fill="white"
                ></path>
              </svg>
            </span>
            <span>
              <svg
                width="14"
                height="16"
                viewBox="0 0 14 16"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  fill-rule="evenodd"
                  clip-rule="evenodd"
                  d="M0.088012 0.571735C0.0310801 0.726729 0 0.910797 0 1.121V14.8786C0 15.0894 0.0311427 15.2736 0.0881839 15.4286L7.32808 7.9997L0.088012 0.571735ZM0.590122 15.9564C0.85223 16.0466 1.18264 15.9995 1.54068 15.7912L10.0736 10.8165L7.83627 8.52109L0.590122 15.9564ZM10.7221 10.4391L13.3647 8.8987C14.2118 8.40415 14.2118 7.59609 13.3647 7.10217L10.7211 5.561L8.34443 7.99966L10.7221 10.4391ZM10.073 5.18317L1.54068 0.209061C1.18252 0.000250885 0.852017 -0.0466058 0.589868 0.0438429L7.83624 7.47828L10.073 5.18317Z"
                  fill="white"
                ></path>
              </svg>
            </span>
          </button>
        </div>
      </div>
      <div class="right-section">
        <img
          class="right-logo"
          src="https://assetscdn1.paytm.com/images/catalog/view_item/850762/1626096258626.png"
          alt="right-logo"
        />
      </div>
    </div>
    <!-- end section - 2 -->

    <!-- recharge section -->
    <div class="recharge-section">
      <div class="inner-section">
        <h1 class="heading">Recharge & Pay Bills on Paytm.</h1>
        <div class="rc-child">
          <div>
            <img
              class="rc-logo"
              src="https://assetscdn1.paytm.com/images/catalog/view_item/733299/1626251017535.png"
              alt=""
            />
            <div class="inner-div">
              <p>Recharge</p>
              <p>Prepaid</p>
              <p>
                Mobile &nbsp;
                <span><i class="fa-solid fa-greater-than"></i></span>
              </p>
            </div>
          </div>
          <div>
            <img
              class="rc-logo"
              src="https://assetscdn1.paytm.com/images/catalog/view_item/733300/1626778824903.png"
              alt=""
            />
            <div class="inner-div">
              <p>Pay</p>
              <p>Rent</p>
              <p>
                Payment &nbsp;
                <span><i class="fa-solid fa-greater-than"></i></span>
              </p>
            </div>
          </div>
          <div>
            <img
              class="rc-logo"
              src="https://assetscdn1.paytm.com/images/catalog/view_item/733308/1626251043534.png"
              alt=""
            />
            <div class="inner-div">
              <p>Pay</p>
              <p>Ekectricity</p>
              <p>
                Bill &nbsp;
                <span><i class="fa-solid fa-greater-than"></i></span>
              </p>
            </div>
          </div>
          <div>
            <img
              class="rc-logo"
              src="https://assetscdn1.paytm.com/images/catalog/view_item/733311/1626251101045.png"
              alt=""
            />
            <div class="inner-div">
              <p>Recharge</p>
              <p>DTH</p>
              <p>
                Connection &nbsp;
                <span><i class="fa-solid fa-greater-than"></i></span>
              </p>
            </div>
          </div>
          <div>
            <img
              class="rc-logo"
              src="https://assetscdn1.paytm.com/images/catalog/view_item/733307/1626251127863.png"
              alt=""
            />
            <div class="inner-div">
              <p>Book</p>
              <p>Gas</p>
              <p>
                Cylinder &nbsp;
                <span><i class="fa-solid fa-greater-than"></i></span>
              </p>
            </div>
          </div>
          <div>
            <img
              class="rc-logo"
              src="https://assetscdn1.paytm.com/images/catalog/view_item/733299/1626251017535.png"
              alt=""
            />
            <div class="inner-div">
              <p>Pay</p>
              <p>Credit</p>
              <p>
                Card Bill &nbsp;
                <span><i class="fa-solid fa-greater-than"></i></span>
              </p>
            </div>
          </div>
          <div>
            <img
              class="rc-logo"
              src="https://assetscdn1.paytm.com/images/catalog/view_item/757701/1626268580682.png"
              alt=""
            />
            <div class="inner-div">
              <p>All</p>
              <p>Payment</p>
              <p>
                Services &nbsp;
                <span><i class="fa-solid fa-greater-than"></i></span>
              </p>
            </div>
          </div>
        </div>
      </div>
      <!-- end recharge section -->

      <!-- Book & Buy section -->
      <div class="book-section">
        <div class="inner-section">
          <h1 class="heading">Book & Buy on Paytm.</h1>
          <div class="rc-child">
            <div>
              <img
                class="bk-logo"
                src="https://assetscdn1.paytm.com/images/catalog/view_item/733295/1626259710574.png"
                alt=""
              />
              <div class="bk-inner-div">
                <p>Movie</p>
                <p>
                  Tickets &nbsp;
                  <span><i class="fa-solid fa-greater-than"></i></span>
                </p>
              </div>
            </div>
            <div>
              <img
                class="bk-logo"
                src="https://assetscdn1.paytm.com/images/catalog/view_item/733296/1626259884425.png"
                alt=""
              />
              <div class="bk-inner-div">
                <p>Flight</p>
                <p>
                  Tickets &nbsp;
                  <span><i class="fa-solid fa-greater-than"></i></span>
                </p>
              </div>
            </div>
            <div>
              <img
                class="bk-logo"
                src="https://assetscdn1.paytm.com/images/catalog/view_item/729996/1626260477699.png"
                alt=""
              />
              <div class="bk-inner-div">
                <p>Bus</p>
                <p>
                  Tickets &nbsp;
                  <span><i class="fa-solid fa-greater-than"></i></span>
                </p>
              </div>
            </div>
            <div>
              <img
                class="bk-logo"
                src="https://assetscdn1.paytm.com/images/catalog/view_item/729997/1626260495975.png"
                alt=""
              />
              <div class="bk-inner-div">
                <p>Train</p>
                <p>
                  Tickets &nbsp;
                  <span><i class="fa-solid fa-greater-than"></i></span>
                </p>
              </div>
            </div>
            <div>
              <img
                class="bk-logo"
                src="https://assetscdn1.paytm.com/images/catalog/view_item/729998/1626259953707.png"
                alt=""
              />
              <div class="bk-inner-div">
                <p>Car &</p>
                <p>
                  Bikes &nbsp;
                  <span><i class="fa-solid fa-greater-than"></i></span>
                </p>
              </div>
            </div>
            <div>
              <img
                class="bk-logo"
                src="https://assetscdn1.paytm.com/images/catalog/view_item/729999/1626259968563.png"
                alt=""
              />
              <div class="bk-inner-div">
                <p>International</p>
                <p>
                  Flights &nbsp;
                  <span><i class="fa-solid fa-greater-than"></i></span>
                </p>
              </div>
            </div>
            <div>
              <img
                class="bk-logo"
                src="https://assetscdn1.paytm.com/images/catalog/view_item/730001/1626450848003.png"
                alt=""
              />
              <div class="bk-inner-div">
                <p>Invest</p>
                <p>
                  in Stocks &nbsp;
                  <span><i class="fa-solid fa-greater-than"></i></span>
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- end Book & Buy section -->
    </div>

    <!-- Payment Instruments section -->
    <div class="ins-section">
      <div class="main-div">
        <h1 class="ins-heading">Paytm Payment Instruments</h1>
        <div class="section-1">
          <div class="left-ins">
            <div class="text-midd">
              <div class="img-text">
                <img
                  class="wallet-logo"
                  src="https://assetscdn1.paytm.com/images/catalog/view/307185/1617861564011.png"
                  alt="wallet-logo"
                />
                <b>
                  Paytm<br />
                  Wallet</b
                >
              </div>
              <h1>
                The Fastest Way to<br />
                Pay In-store & Online.
              </h1>
              <p>
                Load up your Paytm Wallet for free and make payments in a jiffy
                at over 21 million stores, websites and apps. Download the App
              </p>
              <button class="btn">
                Download Paytm App
                <span
                  ><svg
                    width="14"
                    height="16"
                    viewBox="0 0 14 16"
                    fill="none"
                    xmlns="http://www.w3.org/2000/svg"
                  >
                    <path
                      d="M11.6593 15.3557C10.7589 16.1979 9.76546 16.0666 8.81854 15.6695C7.81182 15.2644 6.89149 15.2388 5.82828 15.6695C4.50426 16.2203 3.80155 16.0602 3.00415 15.3557C-1.49786 10.8883 -0.833353 4.08311 4.28331 3.82691C5.52427 3.89096 6.39311 4.48821 7.12406 4.53785C8.21052 4.32489 9.25047 3.71483 10.4133 3.79489C11.8105 3.90377 12.8554 4.43538 13.5531 5.3913C10.6791 7.05657 11.3603 10.7073 14 11.7321C13.4717 13.0691 12.7939 14.3902 11.6576 15.3669L11.6593 15.3557ZM7.02439 3.77888C6.88982 1.79336 8.55939 0.160122 10.4798 0C10.7439 2.28974 8.32017 4.00305 7.02439 3.77888Z"
                      fill="white"
                    ></path>
                  </svg>
                </span>
                <span>
                  <svg
                    width="14"
                    height="16"
                    viewBox="0 0 14 16"
                    fill="none"
                    xmlns="http://www.w3.org/2000/svg"
                  >
                    <path
                      fill-rule="evenodd"
                      clip-rule="evenodd"
                      d="M0.088012 0.571735C0.0310801 0.726729 0 0.910797 0 1.121V14.8786C0 15.0894 0.0311427 15.2736 0.0881839 15.4286L7.32808 7.9997L0.088012 0.571735ZM0.590122 15.9564C0.85223 16.0466 1.18264 15.9995 1.54068 15.7912L10.0736 10.8165L7.83627 8.52109L0.590122 15.9564ZM10.7221 10.4391L13.3647 8.8987C14.2118 8.40415 14.2118 7.59609 13.3647 7.10217L10.7211 5.561L8.34443 7.99966L10.7221 10.4391ZM10.073 5.18317L1.54068 0.209061C1.18252 0.000250885 0.852017 -0.0466058 0.589868 0.0438429L7.83624 7.47828L10.073 5.18317Z"
                      fill="white"
                    ></path>
                  </svg>
                </span>
              </button>
            </div>
          </div>
          <div class="right-ins">
            <img
              class="right-wall-img"
              src="https://assetscdn1.paytm.com/images/catalog/view_item/728701/1618577020961.png"
              alt=""
            />
          </div>
        </div>
        <div class="section-2">
          <div class="left-ins">
            <div class="text-midd">
              <div class="img-text">
                <img
                  class="wallet-logo"
                  src="https://assetscdn1.paytm.com/images/catalog/view/307186/1615957674521.png"
                  alt="wallet-logo"
                />
                <b>
                  UPI Money<br />
                  Transfer</b
                >
              </div>
              <h1>
                Pay anyone directly<br />
                from your bank<br />
                account.
              </h1>
              <p>
                Pay anyone, everywhere. Make contactless & secure payments
                in-stores or online using Paytm Wallet or Directly from your
                Bank Account. Plus, send & receive money from anyone.
              </p>
              <button class="btn">
                Download Paytm App
                <span
                  ><svg
                    width="14"
                    height="16"
                    viewBox="0 0 14 16"
                    fill="none"
                    xmlns="http://www.w3.org/2000/svg"
                  >
                    <path
                      d="M11.6593 15.3557C10.7589 16.1979 9.76546 16.0666 8.81854 15.6695C7.81182 15.2644 6.89149 15.2388 5.82828 15.6695C4.50426 16.2203 3.80155 16.0602 3.00415 15.3557C-1.49786 10.8883 -0.833353 4.08311 4.28331 3.82691C5.52427 3.89096 6.39311 4.48821 7.12406 4.53785C8.21052 4.32489 9.25047 3.71483 10.4133 3.79489C11.8105 3.90377 12.8554 4.43538 13.5531 5.3913C10.6791 7.05657 11.3603 10.7073 14 11.7321C13.4717 13.0691 12.7939 14.3902 11.6576 15.3669L11.6593 15.3557ZM7.02439 3.77888C6.88982 1.79336 8.55939 0.160122 10.4798 0C10.7439 2.28974 8.32017 4.00305 7.02439 3.77888Z"
                      fill="white"
                    ></path>
                  </svg>
                </span>
                <span>
                  <svg
                    width="14"
                    height="16"
                    viewBox="0 0 14 16"
                    fill="none"
                    xmlns="http://www.w3.org/2000/svg"
                  >
                    <path
                      fill-rule="evenodd"
                      clip-rule="evenodd"
                      d="M0.088012 0.571735C0.0310801 0.726729 0 0.910797 0 1.121V14.8786C0 15.0894 0.0311427 15.2736 0.0881839 15.4286L7.32808 7.9997L0.088012 0.571735ZM0.590122 15.9564C0.85223 16.0466 1.18264 15.9995 1.54068 15.7912L10.0736 10.8165L7.83627 8.52109L0.590122 15.9564ZM10.7221 10.4391L13.3647 8.8987C14.2118 8.40415 14.2118 7.59609 13.3647 7.10217L10.7211 5.561L8.34443 7.99966L10.7221 10.4391ZM10.073 5.18317L1.54068 0.209061C1.18252 0.000250885 0.852017 -0.0466058 0.589868 0.0438429L7.83624 7.47828L10.073 5.18317Z"
                      fill="white"
                    ></path>
                  </svg>
                </span>
              </button>
            </div>
          </div>
          <div class="right-ins">
            <img
              class="right-sec-2"
              src="https://assetscdn1.paytm.com/images/catalog/view_item/728702/1626342071104.png"
              alt=""
            />
          </div>
        </div>
        <div class="section-3">
          <div class="left-ins">
            <div class="text-midd">
              <div class="img-text">
                <img
                  class="postpaid-logo"
                  src="https://assetscdn1.paytm.com/images/catalog/view/307191/1613622537678.png"
                  alt="wallet-logo"
                />
              </div>
              <h1>
                Want it?<br />
                No more waiting for it.
              </h1>
              <p>
                With Paytm Postpaid, your wishlist doesn't have to be on the
                waitlist. Shop for the things you want today and pay for them
                next month.
              </p>
              <button class="btn-blue">
                Learn More &nbsp;
                <span><i class="fa-solid fa-greater-than"></i></span>
              </button>
            </div>
          </div>
          <div class="right-ins">
            <img
              class="sec-img-3"
              src="https://assetscdn1.paytm.com/images/catalog/view_item/850764/1626077030984.png"
              alt=""
            />
          </div>
        </div>
      </div>
    </div>
    <!-- End Payment Instruments section -->
  </body>
</html>
