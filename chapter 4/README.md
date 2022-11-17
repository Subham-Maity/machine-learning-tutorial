

<Callout type="info" emoji="💡">
  <div >
    <h5 className="text-left h-10 text-gray-400 font-extrabold md:text-1xl mt-0 mb-0" > Click here if you would like to modify or contribute </h5>
    <a href="https://github.com/Subham-Maity/machine-learning-tutorial" target="_blank">
      <img align="left"
           alt="GitHub"
           src="https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white"
      />
      <p align="left">
        <img src="https://media1.giphy.com/media/2HCaWITqHdJmmEA2b7/giphy.webp?cid=ecf05e47oblnld6xqs4q4svq3w8lnpcltavzi667j872uwq7&rid=giphy.webp&ct=s"  width="50"/>
      </p>
    </a>
  </div>
</Callout>


# Scikit Install

## Message from the Writer
<div class="pb-4"></div>

<div style={{ border:"solid #888", position: "relative" ,opacity: 1 ,borderRadius: "20px" ,overflow: "hidden" }  }>
  <div align="center">
    <div style={{ border: '1px solid #888', padding: '0rem 1rem', textAlign: 'center' }}>
      <h2 align="left">Author</h2>
      <p align="center">
        <img style={{ border:"solid #888", position: "relative" ,opacity: 1 ,borderRadius: "20px" ,overflow: "hidden" }  } src="https://media.giphy.com/media/7VzgMsB6FLCilwS30v/giphy-downsized-large.gif"/>
      </p>
      Here you will learn about Python Scikit learn For ML and Data Science.
      <h7 align="center">
        **Are you exited to learn about the Scikit learn?**
      </h7>
    </div>
  </div></div>

## What is Scikit learn?
<div class="pb-4"></div>

  <div class="font-bold pt-4">
<Feature id="highlighting-card">
Scikit learn is a free machine learning library for the Python programming language. It features various classification, regression and clustering algorithms including support vector machines, random forests, gradient boosting, k-means and DBSCAN, and is designed to interoperate with the Python numerical and scientific libraries NumPy and SciPy.

</Feature>
  </div>
<Callout type="warning" emoji="💡">
Scikit-learn was initially developed by David Cournapeau as a Google summer of code project in 2007. Now it is open source and maintained by a team of developers.
</Callout>

## Installation





<div className="steps-container">
    <style jsx>{`
    .steps-container {
      margin-left: 1rem;
      padding-left: 1.5rem;
      counter-reset: step;
      border-left: 1px solid;
      border-color: rgb(229 231 235/1);
    }
    .steps-container :global(p) {
      counter-increment: step;
    }
    .steps-container :global(p):before {
      content: counter(step);
      display: inline-block;
      position: absolute;
      margin-top: 3px;
      margin-left: -41px;
      width: 33px;
      height: 33px;
      text-align: center;
      text-indent: -1px;
      color: #999;
      border-radius: 100%;
      border: 4px solid #fff;
      background: #f3f3f3;
      line-height: 1.5rem;
      font-size: 1rem;
      font-weight: 400;
    }
  `}</style>

<p className="font-bold">1. Open your terminal and type the following command to install scikit-learn. </p>
  <Feature id="highlighting-card">
    <div  style={{ border:"solid #888", position: "relative" ,opacity: 1 ,borderRadius: "20px" ,overflow: "hidden" ,paddingLeft: "20px" }  } >
  <Cards>
    <Card icon={  <svg width="24" viewBox="0 0 20 20" fill="currentColor">
      <path fillRule="evenodd" d="M11.49 3.17c-.38-1.56-2.6-1.56-2.98 0a1.532 1.532 0 01-2.286.948c-1.372-.836-2.942.734-2.106 2.106.54.886.061 2.042-.947 2.287-1.561.379-1.561 2.6 0 2.978a1.532 1.532 0 01.947 2.287c-.836 1.372.734 2.942 2.106 2.106a1.532 1.532 0 012.287.947c.379 1.561 2.6 1.561 2.978 0a1.533 1.533 0 012.287-.947c1.372.836 2.942-.734 2.106-2.106a1.533 1.533 0 01.947-2.287c1.561-.379 1.561-2.6 0-2.978a1.532 1.532 0 01-.947-2.287c.836-1.372-.734-2.942-2.106-2.106a1.532 1.532 0 01-2.287-.947zM10 13a3 3 0 100-6 3 3 0 000 6z" clipRule="evenodd" />
    </svg>} title="pip" href="/docs/machinelearning/chapter5#installation"/>


  <Tabs items={['Windows', 'macOS', ' Linux']} defaultIndex={1}>

    <Tab>
      ```bash filename="terminal"
      pip install -U scikit-learn
      ```
    </Tab>
    <Tab>

      ```bash filename="terminal"
      pip install -U scikit-learn
      ```
    </Tab>

    <Tab>
      ```bash filename="terminal"
      pip3 install -U scikit-learn
      ```
    </Tab>

  </Tabs>
  </Cards>
    </div>

    <div  style={{ marginTop:"20px" , border:"solid #888", position: "relative" ,opacity: 1 ,borderRadius: "20px" ,overflow: "hidden" ,paddingLeft: "20px" }  } >
  <Cards>
    <Card icon={  <svg width="24" viewBox="0 0 20 20" fill="currentColor">
      <path fillRule="evenodd" d="M11.49 3.17c-.38-1.56-2.6-1.56-2.98 0a1.532 1.532 0 01-2.286.948c-1.372-.836-2.942.734-2.106 2.106.54.886.061 2.042-.947 2.287-1.561.379-1.561 2.6 0 2.978a1.532 1.532 0 01.947 2.287c-.836 1.372.734 2.942 2.106 2.106a1.532 1.532 0 012.287.947c.379 1.561 2.6 1.561 2.978 0a1.533 1.533 0 012.287-.947c1.372.836 2.942-.734 2.106-2.106a1.533 1.533 0 01.947-2.287c1.561-.379 1.561-2.6 0-2.978a1.532 1.532 0 01-.947-2.287c.836-1.372-.734-2.942-2.106-2.106a1.532 1.532 0 01-2.287-.947zM10 13a3 3 0 100-6 3 3 0 000 6z" clipRule="evenodd" />
    </svg>} title="conda" href="/docs/machinelearning/chapter5#installation"/>


    <Tabs items={['Windows', 'macOS', ' Linux']} defaultIndex={1}>

      <Tab>
        ```bash filename="terminal" {1-2}
        conda create -n sklearn-env -c conda-forge scikit-learn
        conda activate sklearn-env
        ```
      </Tab>
      <Tab>

        ```bash filename="terminal" {1-2}
        conda create -n sklearn-env -c conda-forge scikit-learn
        conda activate sklearn-env
        ```
      </Tab>

      <Tab>
        ```bash filename="terminal" {1-2}
        conda create -n sklearn-env -c conda-forge scikit-learn
        conda activate sklearn-env
        ```
      </Tab>

    </Tabs>
  </Cards>
    </div>
  </Feature>
<p className="font-bold">2. In order to check your installation you can use </p>

  <Feature id="highlighting-card">
    <div  style={{ marginTop:"20px" , border:"solid #888", position: "relative" ,opacity: 1 ,borderRadius: "20px" ,overflow: "hidden" ,paddingLeft: "20px" }  } >
    <Cards>
      <Card icon={  <svg width="24" viewBox="0 0 20 20" fill="currentColor">
        <path fillRule="evenodd" d="M11.49 3.17c-.38-1.56-2.6-1.56-2.98 0a1.532 1.532 0 01-2.286.948c-1.372-.836-2.942.734-2.106 2.106.54.886.061 2.042-.947 2.287-1.561.379-1.561 2.6 0 2.978a1.532 1.532 0 01.947 2.287c-.836 1.372.734 2.942 2.106 2.106a1.532 1.532 0 012.287.947c.379 1.561 2.6 1.561 2.978 0a1.533 1.533 0 012.287-.947c1.372.836 2.942-.734 2.106-2.106a1.533 1.533 0 01.947-2.287c1.561-.379 1.561-2.6 0-2.978a1.532 1.532 0 01-.947-2.287c.836-1.372-.734-2.942-2.106-2.106a1.532 1.532 0 01-2.287-.947zM10 13a3 3 0 100-6 3 3 0 000 6z" clipRule="evenodd" />
      </svg>} title="pip" href="/docs/machinelearning/chapter5#installation"/>


      <Tabs items={['Windows', 'macOS', ' Linux']} defaultIndex={1}>

        <Tab>
          ```bash filename="terminal"
          python -m pip show scikit-learn  # to see which version and where scikit-learn is installed
          python -m pip freeze  # to see all packages installed in the active virtualenv
          python -c "import sklearn; sklearn.show_versions()"
          ```
        </Tab>
        <Tab>

          ```bash filename="terminal"
          python -m pip show scikit-learn  # to see which version and where scikit-learn is installed
          python -m pip freeze  # to see all packages installed in the active virtualenv
          python -c "import sklearn; sklearn.show_versions()"
          ```
        </Tab>

        <Tab>
          ```bash filename="terminal"
          python3 -m pip show scikit-learn  # to see which version and where scikit-learn is installed
          python3 -m pip freeze  # to see all packages installed in the active virtualenv
          python3 -c "import sklearn; sklearn.show_versions()"
          ```
        </Tab>

      </Tabs>
    </Cards>
    </div>
    <div  style={{ marginTop:"20px" , border:"solid #888", position: "relative" ,opacity: 1 ,borderRadius: "20px" ,overflow: "hidden" ,paddingLeft: "20px" }  } >
    <Cards>
      <Card icon={  <svg width="24" viewBox="0 0 20 20" fill="currentColor">
        <path fillRule="evenodd" d="M11.49 3.17c-.38-1.56-2.6-1.56-2.98 0a1.532 1.532 0 01-2.286.948c-1.372-.836-2.942.734-2.106 2.106.54.886.061 2.042-.947 2.287-1.561.379-1.561 2.6 0 2.978a1.532 1.532 0 01.947 2.287c-.836 1.372.734 2.942 2.106 2.106a1.532 1.532 0 012.287.947c.379 1.561 2.6 1.561 2.978 0a1.533 1.533 0 012.287-.947c1.372.836 2.942-.734 2.106-2.106a1.533 1.533 0 01.947-2.287c1.561-.379 1.561-2.6 0-2.978a1.532 1.532 0 01-.947-2.287c.836-1.372-.734-2.942-2.106-2.106a1.532 1.532 0 01-2.287-.947zM10 13a3 3 0 100-6 3 3 0 000 6z" clipRule="evenodd" />
      </svg>} title="conda" href="/docs/machinelearning/chapter5#installation"/>


      <Tabs items={['Windows', 'macOS', ' Linux']} defaultIndex={1}>

        <Tab>
          ```bash filename="terminal" {1-3}
          conda list scikit-learn  # to see which scikit-learn version is installed
          conda list  # to see all packages installed in the active conda environment
          python -c "import sklearn; sklearn.show_versions()"
          ```
        </Tab>
        <Tab>

          ```bash filename="terminal" {1-3}
          conda list scikit-learn  # to see which scikit-learn version is installed
          conda list  # to see all packages installed in the active conda environment
          python -c "import sklearn; sklearn.show_versions()"
          ```
        </Tab>

        <Tab>
          ```bash filename="terminal" {1-3}
          conda list scikit-learn  # to see which scikit-learn version is installed
          conda list  # to see all packages installed in the active conda environment
          python -c "import sklearn; sklearn.show_versions()"
          ```
        </Tab>

      </Tabs>
    </Cards>
    </div>

  </Feature>

</div>

For more information on how to install scikit-learn, see the [installation guide](https://scikit-learn.org/stable/install.html).
