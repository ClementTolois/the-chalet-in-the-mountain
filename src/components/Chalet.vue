<template>
    <div class="chalet-wrapper">
        <x3d width="100%" height="800px">
            <scene>
                <transform translation="0 0 0">
                    <!-- <shape>
                        <appearance> 
                            <ImageTexture url="/textures/wood.png"/>
                        </appearance> 
                        <box size="1 1 1"></box>
                    </shape> -->
                    <inline nameSpaceName="Chalet" mapDEFToID="true" url="/models/chalet.x3d" >  </inline>
                </transform>
            </scene>
        </x3d>
    </div>
</template>