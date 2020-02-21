---
layout: default
title: "Common Framework Components"
---
<section class="hero is-light">
  <div class="hero-body">
    <div class="container">
      <h1 class="title is-1">
        Hero Title
       <hr class="bar"></h1>
      <h2 class="subtitle is-3">
        Hero subtitle
      </h2>
      <p>There is no ignorance, and no end to ignorance. There is no old age and death, and no end to old age and death. There is no suffering, no end to suffering, no cause of suffering, no path to follow. There is no attainment of wisdom, and no wisdom to attain.</p>
    </div>
  </div>
</section>
<section class="section">
  <div class="container">
    <h1 class="title">Grid Layout <hr class="bar"></h1>
    <p class="is-size-5">Grid layout is super simple. Set a <code>column</code> inside <code>columns</code> add as many columns as you need, up to 12. If you want to span multiple columns use you can use size helpers (e.g. <code>is-three-fifths</code>, <code>is-half</code>, etc). Or, specify column numbers to span: <code>is-5</code>, <code>is-6</code>.</p>
    <p class="is-size-5">Position your span within the grid with offsets: <code>is-offeset-one-quarter</code>, <code>is-offset-8</code>, etc.</p>
    <img src="https://cl.ly/a7f79be7caf5/Screen%252520Shot%2525202020-01-27%252520at%2525209.09.33%252520AM.png" alt="">

  </div>
</section>
<section class="section">
  <div class="container">
    <h1 class="title">Message Boxes <hr class="bar"></h1>

    <div class="container columns">
      <div class="column">
        <article class="message is-info">
      <div class="message-header">
        <p>Here is a message component using $info color</p>
        <button class="delete" aria-label="delete"></button>
      </div>
      <div class="message-body">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. <strong>Pellentesque risus mi</strong>, tempus quis placerat ut, porta nec nulla. Vestibulum rhoncus ac ex sit amet fringilla. Nullam gravida purus diam, et dictum <a>felis venenatis</a> efficitur. Aenean ac <em>eleifend lacus</em>, in mollis lectus. Donec sodales, arcu et sollicitudin porttitor, tortor urna tempor ligula, id porttitor mi magna a neque. Donec dui urna, vehicula et sem eget, facilisis sodales sem.
      </div>
    </article>
      </div>
  <div class="column"><article class="message is-primary">
  <div class="message-header">
  <p>Here is a message component using $primary color</p>
  <button class="delete" aria-label="delete"></button>
  </div>
  <div class="message-body">
  Lorem ipsum dolor sit amet, consectetur adipiscing elit. <strong>Pellentesque risus mi</strong>, tempus quis placerat ut, porta nec nulla. Vestibulum rhoncus ac ex sit amet fringilla. Nullam gravida purus diam, et dictum <a>felis venenatis</a> efficitur. Aenean ac <em>eleifend lacus</em>, in mollis lectus. Donec sodales, arcu et sollicitudin porttitor, tortor urna tempor ligula, id porttitor mi magna a neque. Donec dui urna, vehicula et sem eget, facilisis sodales sem.
  </div>
  </article></div>
  <div class="column">
        <article class="message is-grey-dark">
      <div class="message-header">
        <p>Here is a message component using $grey-dark color</p>
        <button class="delete" aria-label="delete"></button>
      </div>
      <div class="message-body">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. <strong>Pellentesque risus mi</strong>, tempus quis placerat ut, porta nec nulla. Vestibulum rhoncus ac ex sit amet fringilla. Nullam gravida purus diam, et dictum <a>felis venenatis</a> efficitur. Aenean ac <em>eleifend lacus</em>, in mollis lectus. Donec sodales, arcu et sollicitudin porttitor, tortor urna tempor ligula, id porttitor mi magna a neque. Donec dui urna, vehicula et sem eget, facilisis sodales sem.
      </div>
    </article>
      </div>
    </div>
  </div>
</section>

<section class="section">
  <div class="container">
  <h1 class="title">Tiles—masonry or whatever <hr class="bar"></h1>
  <div class="tile is-ancestor">
  <div class="tile is-vertical is-8">
    <div class="tile">
      <div class="tile is-parent is-vertical">
        <article class="tile is-child notification is-primary">
          <p class="title">Primary color...</p>
          <p class="subtitle">Vertical orientation</p>
        </article>
        <article class="tile is-child notification has-background-grey-dark">
          <p class="title has-text-white">Grey color</p>
          <p class="subtitle has-text-white">All the colors are there</p>
        </article>
        <article class="tile is-child notification is-warning">
          <p class="title">Warning color</p>
          <p class="subtitle">Vertical again..</p>
        </article>
      </div>
      <div class="tile is-parent">
        <article class="tile is-child notification is-info">
          <p class="title">Info color</p>
          <p class="subtitle">With an image</p>
          <figure class="image is-4by3">
            <img src="https://bulma.io/images/placeholders/640x480.png">
          </figure>
        </article>
      </div>
    </div>
    <div class="tile is-parent">
      <article class="tile is-child notification is-danger">
        <p class="title">Danger color</p>
        <p class="subtitle">Aligned with the right tile</p>
        <div class="content">
          <!-- Content -->
        </div>
      </article>
    </div>
  </div>
  <div class="tile is-parent">
    <article class="tile is-child notification is-success">
      <div class="content">
        <p class="title">Success color</p>
        <p class="subtitle">With even more content</p>
        <div class="content">
          <!-- Content -->
        </div>
      </div>
    </article>
  </div>
</div>
  </div>
</section>

<section class="section">
  <div class="container">
  <h1 class="title">Cards <hr class="bar"></h1>
    <div class="columns">
      <div class="column"><div class="card">
  <div class="card-image">
    <figure class="image is-4by3">
      <img src="https://bulma.io/images/placeholders/1280x960.png" alt="Placeholder image">
    </figure>
  </div>
  <div class="card-content">
    <div class="media">
      <div class="media-left">
        <figure class="image is-48x48">
          <img src="https://bulma.io/images/placeholders/96x96.png" alt="Placeholder image">
        </figure>
      </div>
      <div class="media-content">
        <p class="title is-4">John Smith</p>
        <p class="subtitle is-6">@johnsmith</p>
      </div>
    </div>

    <div class="content">
      Lorem ipsum dolor sit amet, consectetur adipiscing elit.
      Phasellus nec iaculis mauris. <a>@bulmaio</a>.
      <a href="#">#css</a> <a href="#">#responsive</a>
      <br>
      <time datetime="2016-1-1">11:09 PM - 1 Jan 2016</time>
    </div>
  </div>
</div></div>
      <div class="column"><div class="card">
  <div class="card-image">
    <figure class="image is-4by3">
      <img src="https://bulma.io/images/placeholders/1280x960.png" alt="Placeholder image">
    </figure>
  </div>
  <div class="card-content">
    <div class="media">
      <div class="media-left">
        <figure class="image is-48x48">
          <img src="https://bulma.io/images/placeholders/96x96.png" alt="Placeholder image">
        </figure>
      </div>
      <div class="media-content">
        <p class="title is-4">John Smith</p>
        <p class="subtitle is-6">@johnsmith</p>
      </div>
    </div>

    <div class="content">
      Lorem ipsum dolor sit amet, consectetur adipiscing elit.
      Phasellus nec iaculis mauris. <a>@bulmaio</a>.
      <a href="#">#css</a> <a href="#">#responsive</a>
      <br>
      <time datetime="2016-1-1">11:09 PM - 1 Jan 2016</time>
    </div>
  </div>
</div></div>
    </div>
  </div>
</section>
<section class="section">
  <div class="container">
  <h1 class="title">More Cards <hr class="bar"></h1>
    <div class="columns">
      <div class="column"><div class="card">
  <header class="card-header">
    <p class="card-header-title">
      Component
    </p>
    <a href="#" class="card-header-icon" aria-label="more options">
      <span class="icon">
        <i class="fas fa-angle-down" aria-hidden="true"></i>
      </span>
    </a>
  </header>
  <div class="card-content">
    <div class="content">
      Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus nec iaculis mauris.
      <a href="#">@bulmaio</a>. <a href="#">#css</a> <a href="#">#responsive</a>
      <br>
      <time datetime="2016-1-1">11:09 PM - 1 Jan 2016</time>
    </div>
  </div>
  <footer class="card-footer">
    <a href="#" class="card-footer-item">Save</a>
    <a href="#" class="card-footer-item">Edit</a>
    <a href="#" class="card-footer-item">Delete</a>
  </footer>
</div></div>
      <div class="column"><div class="card">
  <div class="card-content">
    <p class="title">
      “There are two hard things in computer science: cache invalidation, naming things, and off-by-one errors.”
    </p>
    <p class="subtitle">
      Jeff Atwood
    </p>
  </div>
  <footer class="card-footer">
    <p class="card-footer-item">
      <span>
        View on <a href="https://twitter.com/codinghorror/status/506010907021828096">Twitter</a>
      </span>
    </p>
    <p class="card-footer-item">
      <span>
        Share on <a href="#">Facebook</a>
      </span>
    </p>
  </footer>
</div></div>
    </div>
  </div>
</section>
<section class="section">
  <div class="container">
    <h1 class="title">Form controls <hr class="bar"></h1>

    <div class="field">
  <label class="label">Name</label>
  <div class="control">
    <input class="input" type="text" placeholder="Text input">
  </div>
</div>

<div class="field">
  <label class="label">Username</label>
  <div class="control has-icons-left has-icons-right">
    <input class="input is-success" type="text" placeholder="Text input" value="bulma">
    <span class="icon is-small is-left">
      <i class="fas fa-user"></i>
    </span>
    <span class="icon is-small is-right">
      <i class="fas fa-check"></i>
    </span>
  </div>
  <p class="help is-success">This username is available</p>
</div>

<div class="field">
  <label class="label">Email</label>
  <div class="control has-icons-left has-icons-right">
    <input class="input is-danger" type="email" placeholder="Email input" value="hello@">
    <span class="icon is-small is-left">
      <i class="fas fa-envelope"></i>
    </span>
    <span class="icon is-small is-right">
      <i class="fas fa-exclamation-triangle"></i>
    </span>
  </div>
  <p class="help is-danger">This email is invalid</p>
</div>

<div class="field">
  <label class="label">Subject</label>
  <div class="control">
    <div class="select">
      <select>
        <option>Select dropdown</option>
        <option>With options</option>
      </select>
    </div>
  </div>
</div>

<div class="field">
  <label class="label">Message</label>
  <div class="control">
    <textarea class="textarea" placeholder="Textarea"></textarea>
  </div>
</div>

<div class="field">
  <div class="control">
    <label class="checkbox">
      <input type="checkbox">
      I agree to the <a href="#">terms and conditions</a>
    </label>
  </div>
</div>

<div class="field">
  <div class="control">
    <label class="radio">
      <input type="radio" name="question">
      Yes
    </label>
    <label class="radio">
      <input type="radio" name="question">
      No
    </label>
  </div>
</div>

<div class="field is-grouped">
  <div class="control">
    <button class="button is-link">Submit</button>
  </div>
  <div class="control">
    <button class="button is-link is-light">Cancel</button>
  </div>
</div>
  </div>
</section>
<section class="section">
  <div class="container">
    <h1 class="title">Buttons <hr class="bar"></h1>
    <div class="buttons">
  <button class="button is-primary">Primary</button>
  <button class="button is-link">Link</button>
</div>

<div class="buttons">
  <button class="button is-info">Info</button>
  <button class="button is-success">Success</button>
  <button class="button is-warning">Warning</button>
  <button class="button is-danger">Danger</button>
</div>
  </div>
  <br>
  <div class="container">
  <h2 class="title">Button Sizes</h2>
    <button class="button is-small is-primary">Small</button>
<button class="button is-primary">Default</button>
<button class="button is-normal is-primary">Normal</button>
<button class="button is-medium is-primary">Medium</button>
<button class="button is-large is-primary">Large</button>
  </div>
</section>
<section class="section">
  <div class="container">

  <div class="columns">
    <div class="column"><h1 class="title">Titles <hr class="bar"></h1>
    <h1 class="title is-1">Title 1 <hr class="bar"></h1>
    <h2 class="title is-2">Title 2</h2>
    <h3 class="title is-3">Title 3 (default size)</h3>
    <h4 class="title is-4">Title 4</h4>
    <h5 class="title is-5">Title 5</h5>
    <h6 class="title is-6">Title 6</h6></div>
    <div class="column"><h1 class="title">Subtitles <hr class="bar"></h1>
  <h1 class="subtitle is-1">Subtitle 1 <hr class="bar"></h1>
  <h2 class="subtitle is-2">Subtitle 2</h2>
  <h3 class="subtitle is-3">Subtitle 3</h3>
  <h4 class="subtitle is-4">Subtitle 4</h4>
  <h5 class="subtitle is-5">Subtitle 5</h5>
  <h6 class="subtitle is-6">Subtitle 6</h6></div>
  <div class="column">
    <h1 class="title">Title/Sub <hr class="bar"></h1>
    <p class="title is-1">Title 1</p>
<p class="subtitle is-3">Subtitle 3</p>

<p class="title is-2">Title 2</p>
<p class="subtitle is-4">Subtitle 4</p>

<p class="title is-3">Title 3</p>
<p class="subtitle is-5">Subtitle 5</p>
  </div>
  </div>
  </div>
</section>
<section class="section">
  <div class="container">
  <h1 class="title">Tables <hr class="bar"></h1>
  <table class="table is-bordered is-striped">
  <thead>
    <tr>
      <th><abbr title="Position">Pos</abbr></th>
      <th>Team</th>
      <th><abbr title="Played">Pld</abbr></th>
      <th><abbr title="Won">W</abbr></th>
      <th><abbr title="Drawn">D</abbr></th>
      <th><abbr title="Lost">L</abbr></th>
      <th><abbr title="Goals for">GF</abbr></th>
      <th><abbr title="Goals against">GA</abbr></th>
      <th><abbr title="Goal difference">GD</abbr></th>
      <th><abbr title="Points">Pts</abbr></th>
      <th>Qualification or relegation</th>
    </tr>
  </thead>
  <tfoot>
    <tr>
      <th><abbr title="Position">Pos</abbr></th>
      <th>Team</th>
      <th><abbr title="Played">Pld</abbr></th>
      <th><abbr title="Won">W</abbr></th>
      <th><abbr title="Drawn">D</abbr></th>
      <th><abbr title="Lost">L</abbr></th>
      <th><abbr title="Goals for">GF</abbr></th>
      <th><abbr title="Goals against">GA</abbr></th>
      <th><abbr title="Goal difference">GD</abbr></th>
      <th><abbr title="Points">Pts</abbr></th>
      <th>Qualification or relegation</th>
    </tr>
  </tfoot>
  <tbody>
    <tr>
      <th>1</th>
      <td><a href="https://en.wikipedia.org/wiki/Leicester_City_F.C." title="Leicester City F.C.">Leicester City</a> <strong>(C)</strong>
      </td>
      <td>38</td>
      <td>23</td>
      <td>12</td>
      <td>3</td>
      <td>68</td>
      <td>36</td>
      <td>+32</td>
      <td>81</td>
      <td>Qualification for the <a href="https://en.wikipedia.org/wiki/2016%E2%80%9317_UEFA_Champions_League#Group_stage" title="2016–17 UEFA Champions League">Champions League group stage</a></td>
    </tr>
    <tr>
      <th>2</th>
      <td><a href="https://en.wikipedia.org/wiki/Arsenal_F.C." title="Arsenal F.C.">Arsenal</a></td>
      <td>38</td>
      <td>20</td>
      <td>11</td>
      <td>7</td>
      <td>65</td>
      <td>36</td>
      <td>+29</td>
      <td>71</td>
      <td>Qualification for the <a href="https://en.wikipedia.org/wiki/2016%E2%80%9317_UEFA_Champions_League#Group_stage" title="2016–17 UEFA Champions League">Champions League group stage</a></td>
    </tr>
    <tr>
      <th>3</th>
      <td><a href="https://en.wikipedia.org/wiki/Tottenham_Hotspur_F.C." title="Tottenham Hotspur F.C.">Tottenham Hotspur</a></td>
      <td>38</td>
      <td>19</td>
      <td>13</td>
      <td>6</td>
      <td>69</td>
      <td>35</td>
      <td>+34</td>
      <td>70</td>
      <td>Qualification for the <a href="https://en.wikipedia.org/wiki/2016%E2%80%9317_UEFA_Champions_League#Group_stage" title="2016–17 UEFA Champions League">Champions League group stage</a></td>
    </tr>
    <tr class="is-selected">
      <th>4</th>
      <td><a href="https://en.wikipedia.org/wiki/Manchester_City_F.C." title="Manchester City F.C.">Manchester City</a></td>
      <td>38</td>
      <td>19</td>
      <td>9</td>
      <td>10</td>
      <td>71</td>
      <td>41</td>
      <td>+30</td>
      <td>66</td>
      <td>Qualification for the <a href="https://en.wikipedia.org/wiki/2016%E2%80%9317_UEFA_Champions_League#Play-off_round" title="2016–17 UEFA Champions League">Champions League play-off round</a></td>
    </tr>
    <tr>
      <th>5</th>
      <td><a href="https://en.wikipedia.org/wiki/Manchester_United_F.C." title="Manchester United F.C.">Manchester United</a></td>
      <td>38</td>
      <td>19</td>
      <td>9</td>
      <td>10</td>
      <td>49</td>
      <td>35</td>
      <td>+14</td>
      <td>66</td>
      <td>Qualification for the <a href="https://en.wikipedia.org/wiki/2016%E2%80%9317_UEFA_Europa_League#Group_stage" title="2016–17 UEFA Europa League">Europa League group stage</a></td>
    </tr>
    <tr>
      <th>6</th>
      <td><a href="https://en.wikipedia.org/wiki/Southampton_F.C." title="Southampton F.C.">Southampton</a></td>
      <td>38</td>
      <td>18</td>
      <td>9</td>
      <td>11</td>
      <td>59</td>
      <td>41</td>
      <td>+18</td>
      <td>63</td>
      <td>Qualification for the <a href="https://en.wikipedia.org/wiki/2016%E2%80%9317_UEFA_Europa_League#Group_stage" title="2016–17 UEFA Europa League">Europa League group stage</a></td>
    </tr>
    <tr>
      <th>7</th>
      <td><a href="https://en.wikipedia.org/wiki/West_Ham_United_F.C." title="West Ham United F.C.">West Ham United</a></td>
      <td>38</td>
      <td>16</td>
      <td>14</td>
      <td>8</td>
      <td>65</td>
      <td>51</td>
      <td>+14</td>
      <td>62</td>
      <td>Qualification for the <a href="https://en.wikipedia.org/wiki/2016%E2%80%9317_UEFA_Europa_League#Third_qualifying_round" title="2016–17 UEFA Europa League">Europa League third qualifying round</a></td>
    </tr>
    <tr>
      <th>8</th>
      <td><a href="https://en.wikipedia.org/wiki/Liverpool_F.C." title="Liverpool F.C.">Liverpool</a></td>
      <td>38</td>
      <td>16</td>
      <td>12</td>
      <td>10</td>
      <td>63</td>
      <td>50</td>
      <td>+13</td>
      <td>60</td>
      <td></td>
    </tr>
    <tr>
      <th>9</th>
      <td><a href="https://en.wikipedia.org/wiki/Stoke_City_F.C." title="Stoke City F.C.">Stoke City</a></td>
      <td>38</td>
      <td>14</td>
      <td>9</td>
      <td>15</td>
      <td>41</td>
      <td>55</td>
      <td>−14</td>
      <td>51</td>
      <td></td>
    </tr>
    <tr>
      <th>10</th>
      <td><a href="https://en.wikipedia.org/wiki/Chelsea_F.C." title="Chelsea F.C.">Chelsea</a></td>
      <td>38</td>
      <td>12</td>
      <td>14</td>
      <td>12</td>
      <td>59</td>
      <td>53</td>
      <td>+6</td>
      <td>50</td>
      <td></td>
    </tr>
    <tr>
      <th>11</th>
      <td><a href="https://en.wikipedia.org/wiki/Everton_F.C." title="Everton F.C.">Everton</a></td>
      <td>38</td>
      <td>11</td>
      <td>14</td>
      <td>13</td>
      <td>59</td>
      <td>55</td>
      <td>+4</td>
      <td>47</td>
      <td></td>
    </tr>
    <tr>
      <th>12</th>
      <td><a href="https://en.wikipedia.org/wiki/Swansea_City_A.F.C." title="Swansea City A.F.C.">Swansea City</a></td>
      <td>38</td>
      <td>12</td>
      <td>11</td>
      <td>15</td>
      <td>42</td>
      <td>52</td>
      <td>−10</td>
      <td>47</td>
      <td></td>
    </tr>
    <tr>
      <th>13</th>
      <td><a href="https://en.wikipedia.org/wiki/Watford_F.C." title="Watford F.C.">Watford</a></td>
      <td>38</td>
      <td>12</td>
      <td>9</td>
      <td>17</td>
      <td>40</td>
      <td>50</td>
      <td>−10</td>
      <td>45</td>
      <td></td>
    </tr>
    <tr>
      <th>14</th>
      <td><a href="https://en.wikipedia.org/wiki/West_Bromwich_Albion_F.C." title="West Bromwich Albion F.C.">West Bromwich Albion</a></td>
      <td>38</td>
      <td>10</td>
      <td>13</td>
      <td>15</td>
      <td>34</td>
      <td>48</td>
      <td>−14</td>
      <td>43</td>
      <td></td>
    </tr>
    <tr>
      <th>15</th>
      <td><a href="https://en.wikipedia.org/wiki/Crystal_Palace_F.C." title="Crystal Palace F.C.">Crystal Palace</a></td>
      <td>38</td>
      <td>11</td>
      <td>9</td>
      <td>18</td>
      <td>39</td>
      <td>51</td>
      <td>−12</td>
      <td>42</td>
      <td></td>
    </tr>
    <tr>
      <th>16</th>
      <td><a href="https://en.wikipedia.org/wiki/A.F.C._Bournemouth" title="A.F.C. Bournemouth">AFC Bournemouth</a></td>
      <td>38</td>
      <td>11</td>
      <td>9</td>
      <td>18</td>
      <td>45</td>
      <td>67</td>
      <td>−22</td>
      <td>42</td>
      <td></td>
    </tr>
    <tr>
      <th>17</th>
      <td><a href="https://en.wikipedia.org/wiki/Sunderland_A.F.C." title="Sunderland A.F.C.">Sunderland</a></td>
      <td>38</td>
      <td>9</td>
      <td>12</td>
      <td>17</td>
      <td>48</td>
      <td>62</td>
      <td>−14</td>
      <td>39</td>
      <td></td>
    </tr>
    <tr>
      <th>18</th>
      <td><a href="https://en.wikipedia.org/wiki/Newcastle_United_F.C." title="Newcastle United F.C.">Newcastle United</a> <strong>(R)</strong>
      </td>
      <td>38</td>
      <td>9</td>
      <td>10</td>
      <td>19</td>
      <td>44</td>
      <td>65</td>
      <td>−21</td>
      <td>37</td>
      <td>Relegation to the <a href="https://en.wikipedia.org/wiki/2016%E2%80%9317_Football_League_Championship" title="2016–17 Football League Championship">Football League Championship</a></td>
    </tr>
    <tr>
      <th>19</th>
      <td><a href="https://en.wikipedia.org/wiki/Norwich_City_F.C." title="Norwich City F.C.">Norwich City</a> <strong>(R)</strong>
      </td>
      <td>38</td>
      <td>9</td>
      <td>7</td>
      <td>22</td>
      <td>39</td>
      <td>67</td>
      <td>−28</td>
      <td>34</td>
      <td>Relegation to the <a href="https://en.wikipedia.org/wiki/2016%E2%80%9317_Football_League_Championship" title="2016–17 Football League Championship">Football League Championship</a></td>    </tr>
    <tr>
      <th>20</th>
      <td><a href="https://en.wikipedia.org/wiki/Aston_Villa_F.C." title="Aston Villa F.C.">Aston Villa</a> <strong>(R)</strong>
      </td>
      <td>38</td>
      <td>3</td>
      <td>8</td>
      <td>27</td>
      <td>27</td>
      <td>76</td>
      <td>−49</td>
      <td>17</td>
      <td>Relegation to the <a href="https://en.wikipedia.org/wiki/2016%E2%80%9317_Football_League_Championship" title="2016–17 Football League Championship">Football League Championship</a></td>
    </tr>
  </tbody>
</table>
  </div>
</section>
<section class="section"><div class="container">
  <h1 class="title">Body text elements <hr class="bar"></h1>
  <div class="content">
    <h2 class="title">Blockquote</h2>
    <blockquote>There is no ignorance, and no end to ignorance. There is no old age and death, and no end to old age and death. There is no suffering, no end to suffering, no cause of suffering, no path to follow. There is no attainment of wisdom, and no wisdom to attain. <strong>—Heart Sutra</strong></blockquote>
  </div>
  <div class="container columns">
    <div class="column content">
      <h2 class="title">Ordered Lists</h2>
        <ol type="1">
          <li>Coffee</li>
          <li>Tea</li>
          <li>Milk</li>
        </ol>
        <ol type="A">
          <li>Coffee</li>
          <li>Tea</li>
          <li>Milk</li>
        </ol>
        <ol type="a">
          <li>Coffee</li>
          <li>Tea</li>
          <li>Milk</li>
        </ol>
        <ol type="I">
          <li>Coffee</li>
          <li>Tea</li>
          <li>Milk</li>
        </ol>
        <ol type="i">
          <li>Coffee</li>
          <li>Tea</li>
          <li>Milk</li>
        </ol>
    </div>
    <div class="column">
      <div class="container content is-small">
        <h2>Small Text</h2>
        <p>There is no ignorance, and no end to ignorance. There is no old age and death, and no end to old age and death. There is no suffering, and no end to suffering, no cause of suffering, no path to follow. There is no attainment of wisdom, and no wisdom to attain.</p>
      </div>
      <div class="is-medium content is-medium">
        <h2>Medium Text</h2>
        <p>There is no ignorance, and no end to ignorance. There is no old age and death, and no end to old age and death. There is no suffering, and no end to suffering, no cause of suffering, no path to follow. There is no attainment of wisdom, and no wisdom to attain.</p>
      </div>
      <div class="is-large content is-large">
        <h2>Large Text</h2>
        <p>There is no ignorance, and no end to ignorance. There is no old age and death, and no end to old age and death. There is no suffering, and no end to suffering, no cause of suffering, no path to follow. There is no attainment of wisdom, and no wisdom to attain.</p>
      </div>
    
    </div>
  </div>
</div></section>
<section class="section">
  <div class="container">
    <h2 class="title">Media Box</h2>
    <div class="container columns">
    <div class="box column is-6 is-offset-3">
  <article class="media">
    <div class="media-left">
      <figure class="image is-64x64">
        <img src="https://bulma.io/images/placeholders/128x128.png" alt="Image">
      </figure>
    </div>
    <div class="media-content">
      <div class="content">
        <p>
          <strong>John Smith</strong> <small>@johnsmith</small> <small>31m</small>
          <br>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean efficitur sit amet massa fringilla egestas. Nullam condimentum luctus turpis.
        </p>
      </div>
      <nav class="level is-mobile">
        <div class="level-left">
          <a class="level-item" aria-label="reply">
            <span class="icon is-small">
              <i class="fas fa-reply" aria-hidden="true"></i>
            </span>
          </a>
          <a class="level-item" aria-label="retweet">
            <span class="icon is-small">
              <i class="fas fa-retweet" aria-hidden="true"></i>
            </span>
          </a>
          <a class="level-item" aria-label="like">
            <span class="icon is-small">
              <i class="fas fa-heart" aria-hidden="true"></i>
            </span>
          </a>
        </div>
      </nav>
    </div>
  </article>
</div>
</div>
  </div>
</section>
<section class="section">
  <div class="container">
    <h1 class="title">Progress Bars <hr class="bar"></h1>
    <progress class="progress is-primary" value="15" max="100">15%</progress>
    <progress class="progress is-link" value="30" max="100">30%</progress>
    <progress class="progress is-info" value="45" max="100">45%</progress>
    <progress class="progress is-success" value="60" max="100">60%</progress>
    <progress class="progress is-warning" value="75" max="100">75%</progress>
    <progress class="progress is-danger" value="90" max="100">90%</progress>
  </div>
</section>