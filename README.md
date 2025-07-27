# Pingu Run
## Hi! So, you're interested in playing my game? Well, thanks a lot! :D

**Pingu Run** is a 2D platformer game programmed in **Python** using **pygame**. Navigate your penguin through challenging levels filled with obstacles, enemies, and collectibles!

## Quick Start with UV (Recommended)

The fastest way to get started is using [UV](https://docs.astral.sh/uv/), the modern Python package manager:

### 1. Install UV
```bash
# macOS/Linux
curl -LsSf https://astral.sh/uv/install.sh | sh

# Windows
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"

# Or with pip
pip install uv
```

### 2. Clone and Run
```bash
git clone https://github.com/your-username/Pingu-run-fork.git
cd Pingu-run-fork
uv sync
uv run python runpenguin.py
```

That's it! UV will automatically:
- Install the correct Python version (3.11)
- Create a virtual environment
- Install pygame and all dependencies
- Run the game

## Alternative: Traditional Setup

If you prefer using Conda or pip:

### With Conda
```bash
conda create -n pingu-run python=3.11
conda activate pingu-run
pip install pygame>=2.5.0
python runpenguin.py
```

### With pip/venv
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install pygame>=2.5.0
python runpenguin.py
```

## Development

For development with additional tools:
```bash
uv sync --dev
uv run black .          # Format code
uv run pytest           # Run tests
```

There's a variety of levels in the repository, if you want to try them all you may go to the Pingurun folder and open the file "configPenguin.py".
In the 25th line of this file you should find the variable ' levelsP = "levelsFunc/"', you can change the value "levelsFunc" for any of the levels folders
available (levelsFunc, levelsFuncCB, levelsFuncSB, levelsP).

More levels will be added in the future, so please, look forward to them.

**Enjoy Pingu run! :D**
