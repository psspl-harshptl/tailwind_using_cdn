# Tailwind CSS via CDN

This project demonstrates how to use Tailwind CSS directly in an HTML file using a CDN. This method is great for quick prototyping or simple projects where you don't need a build step.

## How to Use

1.  **Open the project:**
    Simply open the `index.html` file in your browser to see Tailwind CSS in action.

2.  **Using Tailwind CSS via CDN:**
    To add Tailwind CSS to your project, include the following script tag in the `<head>` section of your HTML file:

    ```html
    <script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>
    ```

    You can find the latest CDN link in the [Tailwind CSS Installation](https://tailwindcss.com/docs/installation/play-cdn) documentation.

3.  **Example Usage:**
    In `index.html`, you can see an example of utility classes being used:

    ```html
    <h1 class="text-3xl font-bold underline text-red-600">
        Hello world!
    </h1>
    ```

## Files

-   `index.html`: The main HTML file containing the Tailwind CDN link and example usage.
-   `styles.css`: A custom stylesheet (currently empty) linked in `index.html` for any custom CSS.
