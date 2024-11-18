# 1. How to create a modules in Python:smile:


Hello, in this lesson we will learn how to use markdown to create an engaging readme.

# 2. What we will learn in this lesson:cd:
- How to create a markdown file
- How to write markdown syntax
- How to format code in markdown
- How to embed images in markdown

# Extensions we need are
1. *github* markdown preview by Matt Briener
2. Markdown Emoji by Matt Briener


# Emoji link

You can find all the emoji's here:
<https://www.webfx.com/tools/emoji-cheat-sheet/>

# Other Markdown Editors you can use

1. Mac : **MacDown**
2. Windows: **ghostwriter** or **MarkdownEditor**

# Our Program:kiss:

To load an image use an exclamation in square brackets **![Alternate text]** e.g ! [Image of a cat]
![Reference Image](/Screenshots/screentshot%201.png)
*picture1: useful markdown extensions

To show our code using markdown you can use backticks `` for single code `print("hello world")`
*to show multiple lines of code use three backticks*
Here I have my netlify.toml code
```Javascript
[[redirects]]
  from = "/*"
  to = "/"
  status = 200
```
```Javascript
{
    modal  &&
    <div>
        <div className="h-full w-full fixed top-0 left-0 z-[99]" style={{ background:"rgba(14, 14, 14, 0.58)" }} onClick={() => setModal(false)}></div>
        <div className="bg-white md:w-[400px] w-[80%] flex flex-col fixed top-[50%] left-[50%] pb-[1rem] z-[100] login-modal" style={{ transform: "translate(-50%, -50%)" }}>
            <div className='flex items-center justify-between pt-3 px-6 w-full'>
                <p className='text-[20px] font-[500]'>Confirm Delete</p>
                <p onClick={() => setModal(false)} className='text-gray-500 text-[28px] cursor-pointer'>&times;</p>
            </div>
            <p className='text-center py-6'>Are you sure you want to delete this post?</p>
            <div className='flex justify-between w-[80%] mx-auto gap-4 '>
                <button className='w-full bg-red-600 text-white px-4 text-sm py-1 rounded cursor-pointer'>No</button>
                <button onClick={deletePost} className='w-full bg-blue-600 text-white px-4 text-sm py-1 rounded cursor-pointer'>Yes</button>
            </div>
            {
                modal
            }
        </div>
    </div>
}
```
Running the program we ge the following output

![Image showing the output of the program](/Screenshots/Screenshot%202.png)

* Summary

That's how you can create a nicely formatted README.md file for github
you can find the link to this project here: **github link** <https://github.com/Zainab3121/README.md-files.git>
