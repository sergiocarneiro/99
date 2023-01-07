<div align="center">
	<b>😎 Extensive list of awesome things you can do with <a href="https://awesomeplatform.io">__SOME PLATFORM__ ⚛️</a></b>
</div>

<br />

<p align="center">
	<a href="#section-a">Section A</a>&nbsp;&nbsp;&nbsp;
	<a href="#section-b">Section B</a>&nbsp;&nbsp;&nbsp;
	<a href="#section-c">Section C</a>&nbsp;&nbsp;&nbsp;
	<a href="#section-d">Section D</a>
</p>

<br />

# Welcome!

Here you'll find a collection of practical and concise examples that showcase the different capabilities of [__SOME PLATFORM__](https://awesomeplatform.io).

It should serve as an index, where you get a glimpse of all you can do and then referred to the official documentation for further reading.

If that sounds interesting to you, please consider starring the repo and joining the discussions! ⭐️

<br />

# Section A

## Feature A.1
A short description of the feature.

> Here the "How-to" section is a link.

<p>
	<a href="">How-to</a>&nbsp;&nbsp;&nbsp;
	<a href="">Docs</a>
</p>

<br />

# Section B

## Feature B.1
A short description of the feature.

> Here the "How-to" section is embeded.

<p>
	<a href="">Docs</a>
</p>

<details>
  <summary>How-to</summary>

  ### Markdown is fine here
  And code too.

  ```ts
  export async function loader({ params }: LoaderArgs) {
    const { content, format } = await getImage(params.path);
    return new Response(content, {
      status: 200,
      headers: {
        "Content-Type": `image/${format}`,
      },
    });
  }
  ```
</details>

<br />

# Section C

<br />

# Section D
