<br></br>

<div align="center">
    <img src="/media/logo.png" alt="burla_logo" title="Burla" width="20%" height="auto" />
    <h4>Burla is a python package that makes it incredibly simple to run code on other computers.</h4>
    <p>Burla only has one function:  <code>remote_parallel_map</code>.<br>
    This function only requires two arguments, here's how it works:</p>
    <br></br>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="../media/remote_parallel_map.png" alt="remote_parallel_map" title="Example" width="80%" height="auto" />
    <br></br>
    <p>In this example Burla will execute <code>my_function</code> on every input in <code>my_inputs</code>, at the same time, each on a separate computer in the cloud.<br>
    Burla is <b>fast</b> and <b>scalable</b>. Code starts running within <u>1 second</u> of calling <code>remote_parallel_map</code> on up to <u>1000 CPU's</u>.
    <br></br>
    The goal of Burla is to make it completely seamless to run code on any hardware, in any environment, everything should <i>just work</i>™.<br>
    Here are some features we'll need:
    </p>
    <table>
        <tr>
            <td>
            ⦁ 🐳 Docker Support: Run code in any docker image by passing <code>image=&lt;image-uri&gt;</code>.<br>
            ⦁ ⚙️ GPU Support: Run code on GPU-enabled machines by passing <code>gpu="A100"</code>.<br>
            ⦁ 👨‍💻 Local Developer Experience:<br>
            &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;⚬ Errors on remote computers are re-raised locally.<br>
            &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;⚬ stdout/stderr streamed back to your local machine.<br>
            ⦁ 📦 Packages Sync Automatically: Local python environment quickly cloned on remote machines.<br>
            ⦁ 💾 Simple Network Storage:<br>
            &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;⚬ Remote machines attached to the same fast, persistent, network disk.<br>
            &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;⚬ Manage files in your disk through a simple CLI: <code>> burla nas upload/download/ls/rm ...</code><br>
            ⚡ Always fast: Images, and environments should be cached to maintain &lt; 1 second latency.<br>
            🔧 Simple Installation: Setup burla in your cloud with one command: <code>> burla install gcp/aws</code>
            </td>
        </tr>
    </table><br>
    <p>
    Burla is currently under devlopment and is not ready to be used.<br>
    To sign up for our waitlist go to <a href="https://burla.dev/">burla.dev</a>
    </p>
</div>
