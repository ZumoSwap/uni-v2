# VeRocket Smart Contracts

## Credits
This is a fork of several repositories from VeChain Community public source code.
https://github.com/vechainlabs/uni-v2

All tests passed.

# For Developers
```bash
/uniswap-lib            # math, address, etc
/uniswap-v2-core        # core contracts: factory / pair (pool)
/uniswap-v2-periphery   # user interface: Router02
```

```bash
make install # install dependencies.
make compile # Compile all contracts.
make test # Run all the tests.
```

This is compatible with VeChain after update of thor `1.5.1`

## Testnet

| Contract  |                  Address                   |
| --------- | ------------------------------------------ |
| vVET      | 0x86fb5343bbecffc86185c023a2a6ccc76fc0afd8 |
| vtho      | 0x0000000000000000000000000000456e65726779 |
| factory   | 0xadd8fcf3f0e43aa828f2a55e6d1a9fe5c0d7a679 |
| router02  | 0x91e42759290239a62ac757cf85bb5b74ace57927 |
| vvet/vtho | 0x1e5e9a6540b15a3efa8d4e8fadb82cc8e0e167ca |

## Mainnet

| Contract  |                  Address                   |
| --------- | ------------------------------------------ |
| vVET      | 0x45429a2255e7248e57fce99e7239aed3f84b7a53 |
| vtho      | 0x0000000000000000000000000000456e65726779 |
| factory   | 0xbdc2edaea65b51053ffce8bc0721753c7895e12f |
| router02  | 0x576da7124c7bb65a692d95848276367e5a844d95 |
| vvet/vtho | 0x29a996b0ebb7a77023d091c9f2ca34646bea6ede |

# Disclaimer (I)

- This repo keeps the upstream license of GPL-3.0.
- Neither the name of VeRocket nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.

# Disclaimer (II)
Redistributions of source code must retain this list of conditions and the following disclaimer.

Neither the name of VeChain (VeChain Foundation) nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS “AS IS” AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.