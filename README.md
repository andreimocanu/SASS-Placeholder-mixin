# SASS Placeholder mixin

An easy to use mixin for generating ::placeholder CSS pseudo-elements.

<h3>Usage</h3>

<pre>
input {
  @include placeholder() {
    font-style: italic;
    color: #dedede;
  };
}
</pre>

<h3>Result</h3>

<pre>
input::placeholder {
  font-style: italic;
  color: #dedede;
}
input::-webkit-input-placeholder {
  font-style: italic;
  color: #dedede;
}
input:-ms-input-placeholder {
  font-style: italic;
  color: #dedede;
}
input::-moz-placeholder {
  font-style: italic;
  color: #dedede;
}
input:-moz-placeholder {
  font-style: italic;
  color: #dedede;
}
</pre>
