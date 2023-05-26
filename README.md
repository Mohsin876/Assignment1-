# Assignment1-
/* Reset some default styles */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

/* Set a border and background color for sections and section titles */
.section {
  border: 1px solid black;
  background-color: #e9e9e9;
  float: left;
  width: 33.33%;
}

.section-title {
  position: absolute;
  top: 10px;
  right: 10px;
  padding: 5px;
  background-color: #ffc107;
  border: 1px solid black;
  color: black;
}

/* Set spacing and alignment for the content within sections */
.section p {
  padding: 15px;
}

/* Media queries for responsive layout */
@media (max-width: 991px) {
  .section {
    width: 50%;
  }
  #section3 {
    clear: both;
    width: 100%;
  }
}

@media (max-width: 767px) {
  .section {
    width: 100%;
  }
}
