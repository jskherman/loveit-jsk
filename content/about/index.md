---
title: "About"
subtitle: "Who am I? Ooh, how philosophical of you."
description: "About Je Sian Keith Herman. This section details what he does & everything else you might want to know about him."
slug: "about"
date: 2020-02-02T00:02:02+08:00
lastmod: 2021-02-02T00:02:02+08:00
comments: false
twemoji: true
# toc:
#   auto: false
---

Hi there! 👋 <br/> I'm Je Sian Keith Herman (*you can also call me Jesh*).

I am currently a 3rd year student at [Bicol University][BU] studying [Chemical Engineering][ChE]. I am also living a double life as an impostor thanks to the syndrome of the same name. I like coding and writing on the side[^1] when I have free time. My ~~brain vomit~~ [blog](/blog) is one source where you can find most of my up-to-date written content.

On an unrelated note, I like iced tea 🍹, iced coffee ☕, and ice cream 🍨 in no particular order. I also like RPGs, especially Pokémon, as well as visual novels[^2].

> If you're looking for what I am up to these days, check out my **[Now page](/now)**.

## FAQ

<details>
<summary>Fancy some background music while you're here?</summary>

{{< music url="https://res.cloudinary.com/jskherman/video/upload/v1641875513/Website/isekai_shokudou-main_ost.mp3" name="Restaurant to Another World (Isekai Shokudou) Main Theme" artist="Miho Tsujibayashi" >}} 
</details>
<details>
<summary>How do you pronounce your first name?</summary>

> My first name "Je Sian Keith" is pronounced as /**ʤi ʃan kiːθ**/ (ji shan kith).
</details>
<details>
<summary>What is your horoscope?</summary>

>  It’s Gemini.
</details>

<details>
<summary>Hotel?</summary>

>  Trivago[^3]

</details>

## Contact Me

Want to have a chat with me? Feel free to drop a DM. :smile:
 
These are the platforms[^4] you can find me on:

- Twitter: [@jskherman][twitter]
- LinkedIn: [linkedin.com/in/jskherman][linkedin]

<!-- Footnotes -->

[^1]: This blog is an example project.
[^2]: I got introduced to the genre via [“The World God Only Knows” anime][TWGOK].
[^3]: lol #NotSponsored
[^4]: **Note**: I'm more active on Twitter, so you'll definitely want to ping me there.

<!-- Reference Links -->

[twitter]: https://twitter.com/jskherman
[linkedin]: https://www.linkedin.com/in/jskherman
[github]: https://github.com/jskherman
[TWGOK]: https://myanimelist.net/anime/8525/Kami_nomi_zo_Shiru_Sekai
[BU]: https://bicol-u.edu.ph/
[ChE]: https://www.icheme.org/education/whynotchemeng/

You can also message me directly via the contact form below:

<!-- Google Form -->
<!-- <iframe src="https://docs.google.com/forms/d/e/1FAIpQLScR_cTaQg_CJ6OdpBNJl_mhrT-X7Vey1Fe0mWR552ucKDloWA/viewform?embedded=true" width="640" height="1010" frameborder="0" marginheight="0" marginwidth="0">Loading…</iframe> -->

<form 
  name="contact"
  action="/thank-you/"
  method="POST"
  data-netlify-recaptcha="true"
  data-netlify="true"
>
  <input type="hidden" name="form-name" value="contact" />

  <!-- Text input-->
  <div class="form-group">
    <label for="Name"></label>
    <div>
      <input
        id="contact-form-name"
        name="Name" 
        type="text" 
        placeholder="Name" 
        required="" 
        autocomplete="off"
      >
    </div>
  </div>

  <!-- Text input-->
  <div class="form-group">
    <label for="Email"></label>
    <div>
      <input
        id="contact-form-email"
        name="Email"
        type="email" 
        placeholder="Email Address" 
        required="" 
        autocomplete="off"
      >
    </div>
  </div>

  <!-- Text input-->
  <div class="form-group">
    <label for="Subject"></label>
    <div>
      <input
        id="contact-form-subject"
        name="Subject" 
        type="text" 
        placeholder="Subject" 
        required="" 
        autocomplete="off"
      >
    </div>
  </div>
  
  <!-- Textarea -->
  <div class="form-group">
    <label for=""></label>
    <textarea 
      class="form-control" 
      id="contact-form-message" 
      name="Message" 
      placeholder="What's up?" 
      required="" 
      rows="8"
    ></textarea>
  </div>

  <!-- ReCaptcha -->
  <div data-netlify-recaptcha="true"></div>
  <br/>

  <!-- Button -->
  <div class="form-group">
    <button type="submit" value="Submit" id="Form-submit" class="form-submit">Submit</button>
  </div>

  <style>
      form {
      padding: 15px;
      margin: 5px;
      box-shadow: 0 2px 5px --global-background-color; 
      background: --global-background-color; 
      }
      input, textarea {
      width: calc(100% - 18px);
      padding: 8px;
      margin-bottom: 10px;
      border: 1px solid #1c87c9;
      outline: none;
      caret-color: var(--global-font-color);
      color: var(--global-font-color);
      }
      input::placeholder {
      color: var(--global-font-secondary-color);
      }
      textarea::placeholder {
      color: var(--global-font-secondary-color);
      }

      .form-submit {
      width: calc(100% - 18px);
      padding: 10px;
      border: none;
      background: #1c87c9; 
      font-size: 16px;
      font-weight: 400;
      color: #fff;
      }

      .form-submit:hover {
      background: #2371a0;
      }    
  </style>

</form>