<script>
  import Button from "./Button.svelte";
</script>

<header>
  <h1>Mine components</h1>
</header>

<main>
  <section>
    <h2>Buttons</h2>

    <article>
      <div>
        <h3>Primary</h3>
        <Button>Primary knap</Button>
        <pre><code
            >&lt;script&gt;
  import Button from "./Button.svelte";
&lt;/script&gt;

&lt;Button type="primary"&gt;Første knap&lt;/Button&gt;</code
          ></pre>
      </div>
      <hr />
      <div>
        <h3>Secondary....</h3>

        <Button type="secondary">Første knap</Button>
        <pre><code>{`<Button type="secondary">Første knap</Button>`}</code
          ></pre>
      </div>
      <hr />
      <div>
        <h3>Primary inversed</h3>

        <Button type="primary" inversed={true}>Første knap</Button>
        <pre><code
            >{`<Button type="primary" inversed={true}>Første knap</Button>`}</code
          ></pre>
      </div>
      <hr />
      <div>
        <h3>Secondary inversed</h3>

        <Button type="secondary" inversed={true}>Første knap</Button>
        <pre><code
            >{`<Button type="secondary" inversed={true}>Første knap</Button>`}</code
          ></pre>
      </div>
    </article>
  </section>

  <section>
    <h2>Buttons</h2>

    <article>
      <div>
        <h3>Primary</h3>
        <Button>Primary knap</Button>
        <pre><code
            >&lt;script&gt;
  import Button from "./Button.svelte";
&lt;/script&gt;

&lt;Button type="primary"&gt;Første knap&lt;/Button&gt;</code
          ></pre>
      </div>
      <hr />
      <div>
        <h3>Secondary</h3>

        <Button type="secondary">Første knap</Button>
        <pre><code>{`<Button type="secondary">Første knap</Button>`}</code
          ></pre>
      </div>
      <hr />
      <div>
        <h3>Primary inversed</h3>

        <Button type="primary" inversed={true}>Første knap</Button>
        <pre><code
            >{`<Button type="primary" inversed={true}>Første knap</Button>`}</code
          ></pre>
      </div>
      <hr />
      <div>
        <h3>Secondary inversed</h3>

        <Button type="secondary" inversed={true}>Første knap</Button>
        <pre><code
            >{`<Button type="secondary" inversed={true}>Første knap</Button>`}</code
          ></pre>
      </div>
    </article>
  </section>
</main>
