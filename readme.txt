Example Batch Files & Config File For Locally Hosted Arma Reforger Server

Please note at the time of writing Arma Reforger does not support locally hosted multiplayer servers - this server is for single player use.

TERMS OF USE
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS
OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN
AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH
THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

Install "Arma Reforger Server" from your Steam Library.

Click on the green "Code" button to download the files from this github to your local PC, and unzip or extract them.

Copy conflictstart.bat and conflictconfig.json to the root directory of your server install, usually something like C:\Program Files (x86)\Steam\steamapps\common\Arma Reforger Server

Open conflictstart.bat in your text editor and check the entry "C:\Program Files (x86)\Steam\steamapps\common\Arma Reforger Server\conflictconfig.json" to see that it matches the actual address
of the conflictconfig.json - if you have installed the Server on a different drive, this may need to be changed.

Save any edits.

To start your local server, double click on "conflictstart.bat"

To join your server, go to the community section of the Arma Reforger Multiplayer Server Browser, and click "direct join". Enter ip address of 127.0.0.1 and port of 2001

To access Game Master, in game press "enter" to open the chat box, then type  #login Admin  then press enter. You will then be able to access the Game Master option from the pause menu.

Enjoy, and don't sweat the bugs! 

Thanks, Rob.

List of Scenarios:

 --------------------------------------------------
: Official scenarios (3 entries)
: --------------------------------------------------
: {90F086877C27B6F6}Missions/99_Tutorial.conf (Tutorial)
: {ECC61978EDCC2B5A}Missions/23_Campaign.conf (Conflict)
: {59AD59368755F41A}Missions/21_GM_Eden.conf (Game Master - Everon)
: --------------------------------------------------
: Workshop scenarios (8 entries)
: --------------------------------------------------
: {6EA2E454519E5869}Missions/CAH_Military_Base.conf
: {7C491B1FCC0FF0E1}Missions/CAH_LeMoule.conf
: {F1A1BEA67132113E}Missions/CAH_Castle.conf
: {589945FB9FA7B97D}Missions/CAH_Concrete_Plant.conf
: {2B4183DF23E88249}Missions/CAH_Morton.conf
: {3F2E005F43DBD2F8}Missions/CAH_Briars_Coast.conf
: {9405201CBD22A30C}Missions/CAH_Factory.conf
: {1CD06B409C6FAE56}Missions/CAH_Forest.conf
: --------------------------------------------------

